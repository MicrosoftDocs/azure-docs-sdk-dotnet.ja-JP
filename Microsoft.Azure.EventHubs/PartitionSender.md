<Type Name="PartitionSender" FullName="Microsoft.Azure.EventHubs.PartitionSender">
  <TypeSignature Language="C#" Value="public sealed class PartitionSender : Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionSender extends Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.PartitionSender" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionSender&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type PartitionSender = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.EventHubs.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            この送信元のクラスは、イベント、特定の EventHub パーティションへの送信の論理表現です。 このクラスに関する特定のパーティションにイベントを送信しない場合は、代わりに使用するを使用しないでください<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />です。
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreatePartitionSender(System.String)" />
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateFromConnectionString(System.String)" />
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionSender.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="partitionSender.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.PartitionSender/&lt;CloseAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            閉じのリソースを解放、<see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />です。
            </summary>
        <returns>非同期操作</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventHubClient EventHubClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.EventHubClient EventHubClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionSender.EventHubClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubClient As EventHubClient" />
      <MemberSignature Language="F#" Value="member this.EventHubClient : Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.PartitionSender.EventHubClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.EventHubClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="P:Microsoft.Azure.EventHubs.PartitionSender.EventHubClient" />この PartitionSender に関連付けられています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionSender.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.PartitionSender.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このため、パーティション ID を取得<see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.EventHubs.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.EventHubs.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.Azure.EventHubs.EventData -&gt; System.Threading.Tasks.Task" Usage="partitionSender.SendAsync eventData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData"><see cref="T:Microsoft.Azure.EventHubs.EventData" />送出します。</param>
        <summary>
            送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />特定 EventHub パーティションにします。 この PartitionSender の作成時に、ターゲット パーティションがあらかじめ定義されました。
            この送信パターンでは、一般的な可用性と遅延経由でデータの相関関係が強調されます。
            <para>(およびその sendBatch オーバー ロード) メソッドとして公開されている各 EventHubs に送信する 3 つの方法がある:</para><para>i.<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />または<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>ii です。 <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />または<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>iii です。<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />または<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para>場合は、この種類の送信を使用:<para>します。クライアントは、パーティション間でデータの分布を直接制御する必要があります。ここではクライアントは、イベント ハブ パーティションごとに少なくとも 1 つのセンダがあることを確認する責任があります。</para> <para>b します。ユーザーは特定のパーティションにイベントをダイレクトする平均としてパーティション キーを使用することはできませんも、データとの関連付けにパーティション構成が必要です。</para></summary>
        <returns>ときに完了するタスクを送信操作が行われます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.EventHubs.MessageSizeExceededException">合計サイズ、<see cref="T:Microsoft.Azure.EventHubs.EventData" />サービスによって設定される定義済みの制限を超えています。 既定値は 256 k バイトです。</exception>
        <exception cref="T:Microsoft.Azure.EventHubs.EventHubsException">イベント ハブのサービスでは、操作中に問題が発生しました。</exception>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; eventDatas);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; eventDatas) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (eventDatas As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : seq&lt;Microsoft.Azure.EventHubs.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="partitionSender.SendAsync eventDatas" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.PartitionSender/&lt;SendAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDatas" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDatas">EventHub へ送信するイベントのバッチ</param>
        <summary>
            送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />特定 EventHub パーティションにします。 この PartitionSender の作成時に、対象となるパーティションがあらかじめ定義されました。
            <para>オーバー ロードを参照してください EventHubs、この特定の種類の送信の理解に送信する 3 つの方法がある<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />は、同じ種類の送信と 1 つの送信に使用する<see cref="T:Microsoft.Azure.EventHubs.EventData" />です。</para>バッチを送信する<see cref="T:Microsoft.Azure.EventHubs.EventData" />の次の場合に役に立ちます: <para>i。  効率的な送信 - のバッチ送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />EventHubs のサービスに作成されたセッションの数を最適に使用して、全体的なスループットを最大化します</para>。<para>ii です。 複数の送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />のトランザクションにします。ACID プロパティを実現するために、ゲートウェイ サービスがすべて転送<see cref="T:Microsoft.Azure.EventHubs.EventData" />'s 単一 EventHub へのバッチでパーティションに分割します。</para></summary>
        <returns>送信操作が完了したときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.EventHubs.MessageSizeExceededException">合計サイズ、<see cref="T:Microsoft.Azure.EventHubs.EventData" />サービスによって設定される定義済みの制限を超えています。 既定値は 256 k バイトです。</exception>
        <exception cref="T:Microsoft.Azure.EventHubs.EventHubsException">イベント ハブのサービスでは、操作中に問題が発生しました。</exception>
        <example>
            サンプル コード: 
            <code>
            EventHubClient client = EventHubClient.Create("__connectionString__");
            PartitionSender senderToPartitionOne = client.CreatePartitionSender("1");
                    
            while (true)
            {
                var events = new List&lt;EventData&gt;();
                for (int count = 1; count &lt; 11; count++)
                {
                    var payload = new PayloadEvent(count);
                    byte[] payloadBytes = Encoding.UTF8.GetBytes(JsonConvert.SerializeObject(payload));
                    var sendEvent = new EventData(payloadBytes);
                    var applicationProperties = new Dictionary&lt;string, string&gt;();
                    applicationProperties["from"] = "csharpClient";
                    sendEvent.Properties = applicationProperties;
                    events.Add(sendEvent);
                }
                    
                await senderToPartitionOne.SendAsync(events);
                Console.WriteLine("Sent Batch... Size: {0}", events.Count);
                
            }
            </code></example>
      </Docs>
    </Member>
  </Members>
</Type>