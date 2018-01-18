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
            <span data-ttu-id="b1e52-101">この送信元のクラスは、イベント、特定の EventHub パーティションへの送信の論理表現です。</span><span class="sxs-lookup"><span data-stu-id="b1e52-101">This sender class is a logical representation of sending events to a specific EventHub partition.</span></span> <span data-ttu-id="b1e52-102">このクラスに関する特定のパーティションにイベントを送信しない場合は、代わりに使用するを使用しないでください<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />です。</span><span class="sxs-lookup"><span data-stu-id="b1e52-102">Do not use this class if you do not care about sending events to specific partitions, instead use <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />.</span></span>
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
            <span data-ttu-id="b1e52-103">閉じのリソースを解放、<see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />です。</span><span class="sxs-lookup"><span data-stu-id="b1e52-103">Closes and releases resources for the <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b1e52-104">非同期操作</span><span class="sxs-lookup"><span data-stu-id="b1e52-104">An asynchronous operation</span></span></returns>
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
            <span data-ttu-id="b1e52-105">取得、<see cref="P:Microsoft.Azure.EventHubs.PartitionSender.EventHubClient" />この PartitionSender に関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="b1e52-105">Gets the <see cref="P:Microsoft.Azure.EventHubs.PartitionSender.EventHubClient" /> associated with this PartitionSender.</span></span>
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
            <span data-ttu-id="b1e52-106">このため、パーティション ID を取得<see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />です。</span><span class="sxs-lookup"><span data-stu-id="b1e52-106">Gets the partition ID for this <see cref="T:Microsoft.Azure.EventHubs.PartitionSender" />.</span></span>
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
        <param name="eventData"><span data-ttu-id="b1e52-107"><see cref="T:Microsoft.Azure.EventHubs.EventData" />送出します。</span><span class="sxs-lookup"><span data-stu-id="b1e52-107">the <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to be sent.</span></span></param>
        <summary>
            <span data-ttu-id="b1e52-108">送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />特定 EventHub パーティションにします。</span><span class="sxs-lookup"><span data-stu-id="b1e52-108">Send <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to a specific EventHub partition.</span></span> <span data-ttu-id="b1e52-109">この PartitionSender の作成時に、ターゲット パーティションがあらかじめ定義されました。</span><span class="sxs-lookup"><span data-stu-id="b1e52-109">The target partition is pre-determined when this PartitionSender was created.</span></span>
            <span data-ttu-id="b1e52-110">この送信パターンでは、一般的な可用性と遅延経由でデータの相関関係が強調されます。</span><span class="sxs-lookup"><span data-stu-id="b1e52-110">This send pattern emphasizes data correlation over general availability and latency.</span></span>
            <span data-ttu-id="b1e52-111"><para>(およびその sendBatch オーバー ロード) メソッドとして公開されている各 EventHubs に送信する 3 つの方法がある:</para><para>i.<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" />または<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /> </para> <para>ii です。 <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" />または<see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /> </para> <para>iii です。<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />または<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para>場合は、この種類の送信を使用:<para>します。クライアントは、パーティション間でデータの分布を直接制御する必要があります。ここではクライアントは、イベント ハブ パーティションごとに少なくとも 1 つのセンダがあることを確認する責任があります。</para> <para>b します。ユーザーは特定のパーティションにイベントをダイレクトする平均としてパーティション キーを使用することはできませんも、データとの関連付けにパーティション構成が必要です。</para></span><span class="sxs-lookup"><span data-stu-id="b1e52-111"><para>There are 3 ways to send to EventHubs, each exposed as a method (along with its sendBatch overload):</para><para>i.   <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> or <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para><para>ii.  <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(Microsoft.Azure.EventHubs.EventData,System.String)" /> or <see cref="M:Microsoft.Azure.EventHubs.EventHubClient.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData},System.String)" /></para><para>iii. <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" /> or <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" /></para> Use this type of send if: <para>a. The client wants to take direct control of distribution of data across partitions. In this case client is responsible for making sure there is at least one sender per event hub partition.</para><para>b. User cannot use partition key as a mean to direct events to specific partition, yet there is a need for data correlation with partitioning scheme.</para></span></span></summary>
        <returns><span data-ttu-id="b1e52-112">ときに完了するタスクを送信操作が行われます。</span><span class="sxs-lookup"><span data-stu-id="b1e52-112">A Task that completes when the send operations is done.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.EventHubs.MessageSizeExceededException"><span data-ttu-id="b1e52-113">合計サイズ、<see cref="T:Microsoft.Azure.EventHubs.EventData" />サービスによって設定される定義済みの制限を超えています。</span><span class="sxs-lookup"><span data-stu-id="b1e52-113">the total size of the <see cref="T:Microsoft.Azure.EventHubs.EventData" /> exceeds a pre-defined limit set by the service.</span></span> <span data-ttu-id="b1e52-114">既定値は 256 k バイトです。</span><span class="sxs-lookup"><span data-stu-id="b1e52-114">Default is 256k bytes.</span></span></exception>
        <exception cref="T:Microsoft.Azure.EventHubs.EventHubsException"><span data-ttu-id="b1e52-115">イベント ハブのサービスでは、操作中に問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="b1e52-115">Event Hubs service encountered problems during the operation.</span></span></exception>
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
        <param name="eventDatas"><span data-ttu-id="b1e52-116">EventHub へ送信するイベントのバッチ</span><span class="sxs-lookup"><span data-stu-id="b1e52-116">batch of events to send to EventHub</span></span></param>
        <summary>
            <span data-ttu-id="b1e52-117">送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />特定 EventHub パーティションにします。</span><span class="sxs-lookup"><span data-stu-id="b1e52-117">Send <see cref="T:Microsoft.Azure.EventHubs.EventData" /> to a specific EventHub partition.</span></span> <span data-ttu-id="b1e52-118">この PartitionSender の作成時に、対象となるパーティションがあらかじめ定義されました。</span><span class="sxs-lookup"><span data-stu-id="b1e52-118">The targeted partition is pre-determined when this PartitionSender was created.</span></span>
            <span data-ttu-id="b1e52-119"><para>オーバー ロードを参照してください EventHubs、この特定の種類の送信の理解に送信する 3 つの方法がある<see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />は、同じ種類の送信と 1 つの送信に使用する<see cref="T:Microsoft.Azure.EventHubs.EventData" />です。</para>バッチを送信する<see cref="T:Microsoft.Azure.EventHubs.EventData" />の次の場合に役に立ちます: <para>i。  効率的な送信 - のバッチ送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />EventHubs のサービスに作成されたセッションの数を最適に使用して、全体的なスループットを最大化します</para>。<para>ii です。 複数の送信<see cref="T:Microsoft.Azure.EventHubs.EventData" />のトランザクションにします。ACID プロパティを実現するために、ゲートウェイ サービスがすべて転送<see cref="T:Microsoft.Azure.EventHubs.EventData" />'s 単一 EventHub へのバッチでパーティションに分割します。</para></span><span class="sxs-lookup"><span data-stu-id="b1e52-119"><para> There are 3 ways to send to EventHubs, to understand this particular type of send refer to the overload <see cref="M:Microsoft.Azure.EventHubs.PartitionSender.SendAsync(Microsoft.Azure.EventHubs.EventData)" />, which is the same type of send and is used to send single <see cref="T:Microsoft.Azure.EventHubs.EventData" />. </para> Sending a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s is useful in the following cases: <para>i.    Efficient send - sending a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" /> maximizes the overall throughput by optimally using the number of sessions created to EventHubs' service.</para><para>ii.   Sending multiple <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s in a Transaction. To acheive ACID properties, the Gateway Service will forward all <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s in the batch to a single EventHub partition.</para></span></span></summary>
        <returns><span data-ttu-id="b1e52-120">送信操作が完了したときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="b1e52-120">a Task that completes when the send operation is done.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.EventHubs.MessageSizeExceededException"><span data-ttu-id="b1e52-121">合計サイズ、<see cref="T:Microsoft.Azure.EventHubs.EventData" />サービスによって設定される定義済みの制限を超えています。</span><span class="sxs-lookup"><span data-stu-id="b1e52-121">the total size of the <see cref="T:Microsoft.Azure.EventHubs.EventData" /> exceeds a pre-defined limit set by the service.</span></span> <span data-ttu-id="b1e52-122">既定値は 256 k バイトです。</span><span class="sxs-lookup"><span data-stu-id="b1e52-122">Default is 256k bytes.</span></span></exception>
        <exception cref="T:Microsoft.Azure.EventHubs.EventHubsException"><span data-ttu-id="b1e52-123">イベント ハブのサービスでは、操作中に問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="b1e52-123">Event Hubs service encountered problems during the operation.</span></span></exception>
        <example>
            <span data-ttu-id="b1e52-124">サンプル コード: </span><span class="sxs-lookup"><span data-stu-id="b1e52-124">Sample code:</span></span>
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