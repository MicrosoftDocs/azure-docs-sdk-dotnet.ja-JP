<Type Name="EventProcessorHost" FullName="Microsoft.Azure.EventHubs.Processor.EventProcessorHost">
  <TypeSignature Language="C#" Value="public sealed class EventProcessorHost" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventProcessorHost extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventProcessorHost" />
  <TypeSignature Language="F#" Value="type EventProcessorHost = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Event Hubs のイベント データを処理するためには、ホストを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String, leaseContainerName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost : string * string * string * string * string -&gt; Microsoft.Azure.EventHubs.Processor.EventProcessorHost" Usage="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost (eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString, leaseContainerName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="leaseContainerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">EventHub の名前。</param>
        <param name="consumerGroupName">Event Hub 内のコンシューマー グループの名前です。</param>
        <param name="eventHubConnectionString">Event Hub から受信するための接続文字列。</param>
        <param name="storageConnectionString">リースとチェックポイント処理に使用する Azure ストレージ アカウントへの接続文字列。</param>
        <param name="leaseContainerName">組み込みのリースとチェックポイント マネージャーで使用するための azure Storage コンテナー名。</param>
        <summary>
             Event Hub からイベントを処理する新しいホストを作成します。
             
             <para>Event Hubs は、スケール アウト、高トラフィックのシナリオで頻繁に使用される、ため、通常、プロセスあたり 1 つだけホストおよびする別のコンピューター上のプロセスで実行されます。ただし、通常は 1 台のコンピューター、または 1 つのプロセス内でも、複数のホストを実行するスループット問題がない場合。</para>
             
             このコンス トラクターのオーバー ロードでは、既定、組み込みのリースとチェックポイント マネージャーを使用します。 StorageConnectionString パラメーターで指定された Azure ストレージ アカウントは、レコードのリースとチェックポイントに組み込みの管理者によって使用されます。
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, Microsoft.Azure.EventHubs.Processor.ICheckpointManager checkpointManager, Microsoft.Azure.EventHubs.Processor.ILeaseManager leaseManager);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, class Microsoft.Azure.EventHubs.Processor.ICheckpointManager checkpointManager, class Microsoft.Azure.EventHubs.Processor.ILeaseManager leaseManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.EventHubs.Processor.ICheckpointManager,Microsoft.Azure.EventHubs.Processor.ILeaseManager)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, checkpointManager As ICheckpointManager, leaseManager As ILeaseManager)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost : string * string * string * string * Microsoft.Azure.EventHubs.Processor.ICheckpointManager * Microsoft.Azure.EventHubs.Processor.ILeaseManager -&gt; Microsoft.Azure.EventHubs.Processor.EventProcessorHost" Usage="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubConnectionString, checkpointManager, leaseManager)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="checkpointManager" Type="Microsoft.Azure.EventHubs.Processor.ICheckpointManager" />
        <Parameter Name="leaseManager" Type="Microsoft.Azure.EventHubs.Processor.ILeaseManager" />
      </Parameters>
      <Docs>
        <param name="hostName">プロセッサのホストの名前です。 一意である必要があります。 一意性を確保するための Guid を含むを強くお勧めします。</param>
        <param name="eventHubPath">EventHub の名前。</param>
        <param name="consumerGroupName">Event Hub 内のコンシューマー グループの名前です。</param>
        <param name="eventHubConnectionString">Event Hub から受信するための接続文字列。</param>
        <param name="checkpointManager">パーティションのチェックポイントを処理する ICheckpointManager を実装するオブジェクトします。</param>
        <param name="leaseManager">パーティションのリースを処理する ILeaseManager を実装するオブジェクトします。</param>
        <summary>
            Event Hub からイベントを処理する新しいホストを作成します。
            
            <para>このコンス トラクターのオーバー ロードは、最大限の柔軟性を許可します。このいずれかにより、呼び出し元もプロセッサ ホストの名前を指定することができます。オーバー ロードでは、呼び出し元組み込み済みの Azure Storage に基づくを置換する独自のリースとチェックポイントの管理を提供することもできます。</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorHost (string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName, string storageBlobPrefix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName, string eventHubPath, string consumerGroupName, string eventHubConnectionString, string storageConnectionString, string leaseContainerName, string storageBlobPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String, eventHubPath As String, consumerGroupName As String, eventHubConnectionString As String, storageConnectionString As String, leaseContainerName As String, Optional storageBlobPrefix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost : string * string * string * string * string * string * string -&gt; Microsoft.Azure.EventHubs.Processor.EventProcessorHost" Usage="new Microsoft.Azure.EventHubs.Processor.EventProcessorHost (hostName, eventHubPath, consumerGroupName, eventHubConnectionString, storageConnectionString, leaseContainerName, storageBlobPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="eventHubConnectionString" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="leaseContainerName" Type="System.String" />
        <Parameter Name="storageBlobPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">このイベント プロセッサ ホストの名前。 メソッドのノートを参照してください。</param>
        <param name="eventHubPath">EventHub の名前。</param>
        <param name="consumerGroupName">Event Hub 内のコンシューマー グループの名前です。</param>
        <param name="eventHubConnectionString">Event Hub から受信するための接続文字列。</param>
        <param name="storageConnectionString">リースとチェックポイント処理に使用する Azure ストレージ アカウントへの接続文字列。</param>
        <param name="leaseContainerName">組み込みのリースとチェックポイント マネージャーで使用するための azure Storage コンテナー名。</param>
        <param name="storageBlobPrefix">ストレージ コンテナー内の blob の名前を付けるときに使用されるプレフィックス。</param>
        <summary>
            Event Hub からイベントを処理する新しいホストを作成します。
            
            <para>このコンス トラクターのオーバー ロードでは、既定、組み込みのリースとチェックポイント マネージャーを使用します。</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.ConsumerGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンシューマー グループ名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            イベント ハブのパスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プロセッサのホスト名を返します。
            プロセッサのホスト名が自動的に生成された場合、これは、これを取得する唯一の方法。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionManagerOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions PartitionManagerOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions PartitionManagerOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionManagerOptions As PartitionManagerOptions" />
      <MemberSignature Language="F#" Value="member this.PartitionManagerOptions : Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定、<see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" />インスタンスによって使用される、<see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />オブジェクト。</summary>
        <value><see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.PartitionManagerOptions" /> インスタンス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;T&gt; () where T : Microsoft.Azure.EventHubs.Processor.IEventProcessornew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;.ctor (class Microsoft.Azure.EventHubs.Processor.IEventProcessor) T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorAsync``1" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorAsync(Of T As {IEventProcessorNew}) () As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorAsync : unit -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.Azure.EventHubs.Processor.IEventProcessor and 'T : (new : unit -&gt; 'T))" Usage="eventProcessorHost.RegisterEventProcessorAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.EventHubs.Processor.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">アプリケーション固有の実装<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />です。</typeparam>
        <summary>
            これにより、登録<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />を使用してホストで実装が<see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />です。  
            これもホストを起動し、パーティションの配布プロセスへの参加を開始するようにします。
            </summary>
        <returns>EventProcessorHost インスタンスを示すためにタスクが開始されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;T&gt; (Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions) where T : Microsoft.Azure.EventHubs.Processor.IEventProcessornew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorAsync&lt;.ctor (class Microsoft.Azure.EventHubs.Processor.IEventProcessor) T&gt;(class Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorAsync``1(Microsoft.Azure.EventHubs.Processor.EventProcessorOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorAsync(Of T As {IEventProcessorNew}) (processorOptions As EventProcessorOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorAsync : Microsoft.Azure.EventHubs.Processor.EventProcessorOptions -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.Azure.EventHubs.Processor.IEventProcessor and 'T : (new : unit -&gt; 'T))" Usage="eventProcessorHost.RegisterEventProcessorAsync processorOptions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.EventHubs.Processor.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="processorOptions" Type="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">アプリケーション固有の実装<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />です。</typeparam>
        <param name="processorOptions">
          <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" />EventHub の特定のパーティションの所有権を取得したときに作成されたメッセージ ポンプのさまざまな側面を制御します。</param>
        <summary>
            これにより、登録<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />を使用してホストで実装が<see cref="T:Microsoft.Azure.EventHubs.Processor.DefaultEventProcessorFactory`1" />です。  
            これもホストを起動し、パーティションの配布プロセスへの参加を開始するようにします。
            </summary>
        <returns>EventProcessorHost インスタンスを示すためにタスクが開始されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync (Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync(class Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorFactoryAsync(Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorFactoryAsync (factory As IEventProcessorFactory) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorFactoryAsync : Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.RegisterEventProcessorFactoryAsync factory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />
      </Parameters>
      <Docs>
        <param name="factory">インスタンス<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />実装します。</param>
        <summary>
            これにより、登録<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />実装のインスタンスを作成するために使用するホストと<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />所有権パーティションの場合。  これもホストを起動し、パーティションの配布プロセスへの参加を開始するようにします。
            </summary>
        <returns>EventProcessorHost インスタンスを示すためにタスクが開始されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterEventProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync (Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory, Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterEventProcessorFactoryAsync(class Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory factory, class Microsoft.Azure.EventHubs.Processor.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.RegisterEventProcessorFactoryAsync(Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory,Microsoft.Azure.EventHubs.Processor.EventProcessorOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterEventProcessorFactoryAsync (factory As IEventProcessorFactory, processorOptions As EventProcessorOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterEventProcessorFactoryAsync : Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory * Microsoft.Azure.EventHubs.Processor.EventProcessorOptions -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.RegisterEventProcessorFactoryAsync (factory, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.Processor.EventProcessorHost/&lt;RegisterEventProcessorFactoryAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />
        <Parameter Name="processorOptions" Type="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <param name="factory">インスタンス<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />実装します。</param>
        <param name="processorOptions">
          <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.EventProcessorOptions" />EventHub の特定のパーティションの所有権を取得したときに作成されたメッセージ ポンプのさまざまな側面を制御します。</param>
        <summary>
            これにより、登録<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />実装のインスタンスを作成するために使用するホストと<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />所有権パーティションの場合。  これもホストを起動し、パーティションの配布プロセスへの参加を開始するようにします。
            </summary>
        <returns>EventProcessorHost インスタンスを示すためにタスクが開始されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterEventProcessorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterEventProcessorAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterEventProcessorAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorHost.UnregisterEventProcessorAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterEventProcessorAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterEventProcessorAsync : unit -&gt; System.Threading.Tasks.Task" Usage="eventProcessorHost.UnregisterEventProcessorAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.Processor.EventProcessorHost/&lt;UnregisterEventProcessorAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            イベントの処理を停止します。  シャット ダウンが完了するまでは返しません。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>