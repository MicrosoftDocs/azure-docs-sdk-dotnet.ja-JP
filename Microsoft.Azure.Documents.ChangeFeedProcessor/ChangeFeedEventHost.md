<Type Name="ChangeFeedEventHost" FullName="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost">
  <TypeSignature Language="C#" Value="public class ChangeFeedEventHost" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ChangeFeedEventHost extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />
  <TypeSignature Language="VB.NET" Value="Public Class ChangeFeedEventHost" />
  <TypeSignature Language="F#" Value="type ChangeFeedEventHost = class&#xA;    interface IPartitionObserver&lt;DocumentServiceLease&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.17.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            変更を配布するための単純なホストは、オブザーバーとなり、これらのオブザーバー スケールの間でイベントをフィードです。
            そのインスタンスは、負荷を分散し、により、動的スケーリングします。
              - インスタンスまたはオブザーバー パーティション分割コレクション内のパーティションに分散されます。
              - 新しいインスタンスは、配布を等しくする既存のインスタンスからのリースを受け取ります。
              - インスタンスが停止した場合、リースは残りのインスタンス間で分散されます。
            1 つのホストと VM が多くの変更フィード イベントを処理できるようにするため、パーティション数が高いシナリオでは便利です。
            クライアント アプリケーションを実装する必要がある<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver" />ChangeFeedEventHost にプロセッサの実装を登録します。
            </summary>
    <remarks>
            パーティションのリースを管理するための補助ドキュメント コレクションを使用します。
            すべての EventProcessorHost インスタンスは、次の 2 つのタスクを実行します。
                1) リースを更新します。 ホストが所有する現在のリースの追跡し、継続的に、リースの更新では保持します。
                2) リースを取得します。 各インスタンスは継続的に、すべてのリースをバランスの取れた状態にする、システムの取得する必要がありますが、リースがあるかどうかは確認をポーリングします。
                </remarks>
    <example>
      <code language="c#"><![CDATA[
            class DocumentFeedObserver : IChangeFeedObserver
            {
                private static int s_totalDocs = 0;
                public Task OpenAsync(ChangeFeedObserverContext context)
                {
                    Console.WriteLine("Worker opened, {0}", context.PartitionKeyRangeId);
                    return Task.CompletedTask;  // Requires targeting .NET 4.6+.
                }
                public Task CloseAsync(ChangeFeedObserverContext context, ChangeFeedObserverCloseReason reason)
                {
                    Console.WriteLine("Worker closed, {0}", context.PartitionKeyRangeId);
                    return Task.CompletedTask;
                }
                public Task ProcessChangesAsync(ChangeFeedObserverContext context, IReadOnlyList<Document> docs)
                {
                    Console.WriteLine("Change feed: total {0} doc(s)", Interlocked.Add(ref s_totalDocs, docs.Count));
                    return Task.CompletedTask;
                }
            }
            static async Task StartChangeFeedHost()
            {
                string hostName = Guid.NewGuid().ToString();
                DocumentCollectionInfo documentCollectionLocation = new DocumentCollectionInfo
                {
                    Uri = new Uri("https://YOUR_SERVICE.documents.azure.com:443/"),
                    MasterKey = "YOUR_SECRET_KEY==",
                    DatabaseName = "db1",
                    CollectionName = "documents"
                };
                DocumentCollectionInfo leaseCollectionLocation = new DocumentCollectionInfo
                {
                    Uri = new Uri("https://YOUR_SERVICE.documents.azure.com:443/"),
                    MasterKey = "YOUR_SECRET_KEY==",
                    DatabaseName = "db1",
                    CollectionName = "leases"
                };
                Console.WriteLine("Main program: Creating ChangeFeedEventHost...");
                ChangeFeedEventHost host = new ChangeFeedEventHost(hostName, documentCollectionLocation, leaseCollectionLocation);
                await host.RegisterObserverAsync<DocumentFeedObserver>();
                Console.WriteLine("Main program: press Enter to stop...");
                Console.ReadLine();
                await host.UnregisterObserversAsync();
            }
            ]]></code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedEventHost (string hostName, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.#ctor(System.String,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, documentCollectionLocation As DocumentCollectionInfo, auxCollectionLocation As DocumentCollectionInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost : string * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo -&gt; Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" Usage="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost (hostName, documentCollectionLocation, auxCollectionLocation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="documentCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
        <Parameter Name="auxCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
      </Parameters>
      <Docs>
        <param name="hostName">このホストの一意の名前。</param>
        <param name="documentCollectionLocation">変更を監視する DocumentDB コレクションの位置を指定します。</param>
        <param name="auxCollectionLocation">負荷分散の補助的なデータの場所を指定のインスタンス<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />です。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedEventHost (string hostName, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation, Microsoft.Azure.Documents.Client.ChangeFeedOptions changeFeedOptions, Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions hostOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo documentCollectionLocation, class Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo auxCollectionLocation, class Microsoft.Azure.Documents.Client.ChangeFeedOptions changeFeedOptions, class Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions hostOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.#ctor(System.String,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo,Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo,Microsoft.Azure.Documents.Client.ChangeFeedOptions,Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost : string * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo * Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo * Microsoft.Azure.Documents.Client.ChangeFeedOptions * Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions -&gt; Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" Usage="new Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost (hostName, documentCollectionLocation, auxCollectionLocation, changeFeedOptions, hostOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="documentCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
        <Parameter Name="auxCollectionLocation" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.DocumentCollectionInfo" />
        <Parameter Name="changeFeedOptions" Type="Microsoft.Azure.Documents.Client.ChangeFeedOptions" />
        <Parameter Name="hostOptions" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions" />
      </Parameters>
      <Docs>
        <param name="hostName">このホストの一意の名前。</param>
        <param name="documentCollectionLocation">変更を監視する DocumentDB コレクションの位置を指定します。</param>
        <param name="auxCollectionLocation">負荷分散の補助的なデータの場所を指定のインスタンス<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />です。</param>
        <param name="changeFeedOptions">Microsoft.AzureDocuments.DocumentClient.CreateChangeFeedQuery API に渡すオプションです。</param>
        <param name="hostOptions">負荷分散を制御する追加のオプション<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />インスタンス。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEstimatedRemainingWork">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; GetEstimatedRemainingWork ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; GetEstimatedRemainingWork() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.GetEstimatedRemainingWork" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEstimatedRemainingWork () As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.GetEstimatedRemainingWork : unit -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="changeFeedEventHost.GetEstimatedRemainingWork " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;GetEstimatedRemainingWork&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            非同期的に現在の既存リースを確認し、専用のパーティションごとの残存作業時間の概算を計算します。
            </summary>
        <returns>処理するドキュメントの残りの量の見積もり</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>インスタンスの一意の名前をあるホスト名を取得します。</summary>
        <value>ホスト名です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterObserverAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterObserverAsync&lt;T&gt; () where T : Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObservernew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterObserverAsync&lt;.ctor (class Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.RegisterObserverAsync``1" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterObserverAsync(Of T As {IChangeFeedObserverNew}) () As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterObserverAsync : unit -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver and 'T : (new : unit -&gt; 'T))" Usage="changeFeedEventHost.RegisterObserverAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;RegisterObserverAsync&gt;d__23`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">特定のアプリケーション イベント オブザーバーの実装です。</typeparam>
        <summary>非同期的に、オブザーバー インターフェイスの実装をホストに登録します。
            また、このメソッドは、ホストを開始し、により、パーティションの配布プロセスへの参加を開始するようにします。</summary>
        <returns>タスクを示す、<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />インスタンスが開始します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterObserverFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterObserverFactoryAsync (Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterObserverFactoryAsync(class Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.RegisterObserverFactoryAsync(Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterObserverFactoryAsync (factory As IChangeFeedObserverFactory) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterObserverFactoryAsync : Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory -&gt; System.Threading.Tasks.Task" Usage="changeFeedEventHost.RegisterObserverFactoryAsync factory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;RegisterObserverFactoryAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserverFactory" />
      </Parameters>
      <Docs>
        <param name="factory">特定のアプリケーション イベント オブザーバーの出荷時の実装です。</param>
        <summary>
            非同期的にオブザーバー ファクトリの実装をホストに登録します。
            また、このメソッドは、ホストを開始し、により、パーティションの配布プロセスへの参加を開始するようにします。
            </summary>
        <returns>タスクを示す、<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />インスタンスが開始します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterObserversAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterObserversAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterObserversAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost.UnregisterObserversAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterObserversAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterObserversAsync : unit -&gt; System.Threading.Tasks.Task" Usage="changeFeedEventHost.UnregisterObserversAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost/&lt;UnregisterObserversAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>ホスト インスタンスを非同期的に終了します。 このメソッドは、現在保持されているすべてのパーティションでリースを維持し、正常にシャット ダウン オブジェクトでメソッドを呼び出すことによって各ホスト インスタンスを有効にします。</summary>
        <returns>ホスト インスタンスを示すタスクが停止しました。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>