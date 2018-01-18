<Type Name="PartitionReceiver" FullName="Microsoft.Azure.EventHubs.PartitionReceiver">
  <TypeSignature Language="C#" Value="public abstract class PartitionReceiver : Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PartitionReceiver extends Microsoft.Azure.EventHubs.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.PartitionReceiver" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PartitionReceiver&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type PartitionReceiver = class&#xA;    inherit ClientEntity" />
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
            <span data-ttu-id="6d9ea-101">これは、EventHub パーティションからの受信の論理表現です。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-101">This is a logical representation of receiving from a EventHub partition.</span></span>
            <span data-ttu-id="6d9ea-102"><para>PartitionReceiver が、ConsumerGroup に関連付けられている + パーティションの組み合わせ。エポックを作成する場合はベース PartitionReceiver (つまり PartitionReceiver.Epoch! = 0) ConsumerGroup + パーティションあたり 1 つ以上のアクティブな受信機を持つことはできませんコンボです。ConsumerGroup あたり複数の受信者を持てる + エポック以外の受信側との組み合わせをパーティションします。</para></span><span class="sxs-lookup"><span data-stu-id="6d9ea-102"><para> A PartitionReceiver is tied to a ConsumerGroup + Partition combination. If you are creating an epoch based PartitionReceiver (i.e. PartitionReceiver.Epoch != 0) you cannot have more than one active receiver per ConsumerGroup + Partition combo. You can have multiple receivers per ConsumerGroup + Partition combination with non-epoch receivers. </para></span></span></summary>
    <remarks>To be added.</remarks>
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.String)" />
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.String,System.Int64)" />
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateReceiver(System.String,System.String,System.String,Microsoft.Azure.EventHubs.ReceiverOptions)" />
    <altmember cref="M:Microsoft.Azure.EventHubs.EventHubClient.CreateEpochReceiver(System.String,System.String,System.String,System.Int64,Microsoft.Azure.EventHubs.ReceiverOptions)" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal PartitionReceiver (Microsoft.Azure.EventHubs.EventHubClient eventHubClient, string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, Nullable&lt;DateTime&gt; startTime, Nullable&lt;long&gt; epoch, Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.EventHubs.EventHubClient eventHubClient, string consumerGroupName, string partitionId, string startOffset, bool offsetInclusive, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;int64&gt; epoch, class Microsoft.Azure.EventHubs.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.#ctor(Microsoft.Azure.EventHubs.EventHubClient,System.String,System.String,System.String,System.Boolean,System.Nullable{System.DateTime},System.Nullable{System.Int64},Microsoft.Azure.EventHubs.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.PartitionReceiver : Microsoft.Azure.EventHubs.EventHubClient * string * string * string * bool * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.EventHubs.ReceiverOptions -&gt; Microsoft.Azure.EventHubs.PartitionReceiver" Usage="new Microsoft.Azure.EventHubs.PartitionReceiver (eventHubClient, consumerGroupName, partitionId, startOffset, offsetInclusive, startTime, epoch, receiverOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="eventHubClient" Type="Microsoft.Azure.EventHubs.EventHubClient" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="epoch" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="receiverOptions" Type="Microsoft.Azure.EventHubs.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="eventHubClient"></param>
        <param name="consumerGroupName"></param>
        <param name="partitionId"></param>
        <param name="startOffset"></param>
        <param name="offsetInclusive"></param>
        <param name="startTime"></param>
        <param name="epoch"></param>
        <param name="receiverOptions"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public override sealed System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="partitionReceiver.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6d9ea-103">閉じに関連付けられているリソースを解放<see cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-103">Closes and releases resources associated with <see cref="T:Microsoft.Azure.EventHubs.PartitionReceiver" />.</span></span>
            </summary>
        <returns><span data-ttu-id="6d9ea-104">非同期操作</span><span class="sxs-lookup"><span data-stu-id="6d9ea-104">An asynchronous operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.ConsumerGroupName" />
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
            <span data-ttu-id="6d9ea-105">コンシューマー グループ名</span><span class="sxs-lookup"><span data-stu-id="6d9ea-105">The Consumer Group Name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultConsumerGroupName">
      <MemberSignature Language="C#" Value="public static readonly string DefaultConsumerGroupName;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string DefaultConsumerGroupName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.EventHubs.PartitionReceiver.DefaultConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultConsumerGroupName As String " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultConsumerGroupName : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.DefaultConsumerGroupName" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="6d9ea-106">既定のコンシューマー グループ名: $Default です。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-106">The default consumer group name: $Default.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOfStream">
      <MemberSignature Language="C#" Value="public static readonly string EndOfStream;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string EndOfStream" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.EventHubs.PartitionReceiver.EndOfStream" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly EndOfStream As String " />
      <MemberSignature Language="F#" Value=" staticval mutable EndOfStream : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.EndOfStream" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="6d9ea-107">ストリームの末尾を示す定数です。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-107">The constant that denotes the end of a stream.</span></span> <span data-ttu-id="6d9ea-108">これは、/時刻のオフセット値の特定のポイントではなく、最新のイベントからの受信を開始するレシーバー作成のオフセットの引数として使用できます。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-108">This can be used as an offset argument in receiver creation to start receiving from the latest event, instead of a specific point in time/offset value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Epoch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Epoch As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Epoch : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d9ea-109">この受信者は現在使用しているパーティションの所有権をエポック値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-109">Get the epoch value that this receiver is currently using for partition ownership.</span></span>
            <span data-ttu-id="6d9ea-110"><para>値が null の場合この受信者は、エポックに基づいたレシーバーではありません。</para></span><span class="sxs-lookup"><span data-stu-id="6d9ea-110"><para>A value of null means this receiver is not an epoch-based receiver.</para></span></span></summary>
        <value><span data-ttu-id="6d9ea-111">この受信者は現在使用しているパーティションの所有権をエポック値。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-111">the epoch value that this receiver is currently using for partition ownership.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.EventHubClient EventHubClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.EventHubClient EventHubClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.EventHubClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubClient As EventHubClient" />
      <MemberSignature Language="F#" Value="member this.EventHubClient : Microsoft.Azure.EventHubs.EventHubClient" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.EventHubClient" />
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
            <span data-ttu-id="6d9ea-112">この PartitionReceiver EventHubClient が作成されました。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-112">The EventHubClient this PartitionReceiver was created from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OffsetInclusive">
      <MemberSignature Language="C#" Value="protected bool OffsetInclusive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OffsetInclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.OffsetInclusive" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property OffsetInclusive As Boolean" />
      <MemberSignature Language="F#" Value="member this.OffsetInclusive : bool" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.OffsetInclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnCloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.OnCloseAsync" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnCloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="partitionReceiver.OnCloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReceiveAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt; OnReceiveAsync (int maxMessageCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.EventHubs.EventData&gt;&gt; OnReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.OnReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnReceiveAsync (maxMessageCount As Integer, waitTime As TimeSpan) As Task(Of IList(Of EventData))" />
      <MemberSignature Language="F#" Value="abstract member OnReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;" Usage="partitionReceiver.OnReceiveAsync (maxMessageCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"></param>
        <param name="waitTime"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSetReceiveHandler">
      <MemberSignature Language="C#" Value="protected abstract void OnSetReceiveHandler (Microsoft.Azure.EventHubs.IPartitionReceiveHandler receiveHandler);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnSetReceiveHandler(class Microsoft.Azure.EventHubs.IPartitionReceiveHandler receiveHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.OnSetReceiveHandler(Microsoft.Azure.EventHubs.IPartitionReceiveHandler)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnSetReceiveHandler (receiveHandler As IPartitionReceiveHandler)" />
      <MemberSignature Language="F#" Value="abstract member OnSetReceiveHandler : Microsoft.Azure.EventHubs.IPartitionReceiveHandler -&gt; unit" Usage="partitionReceiver.OnSetReceiveHandler receiveHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveHandler" Type="Microsoft.Azure.EventHubs.IPartitionReceiveHandler" />
      </Parameters>
      <Docs>
        <param name="receiveHandler"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.PartitionId" />
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
            <span data-ttu-id="6d9ea-113">EventHub パーティション識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-113">Get the EventHub partition identifier.</span></span>
            </summary>
        <value><span data-ttu-id="6d9ea-114">この受信者がデータをフェッチは、パーティションを表す識別子</span><span class="sxs-lookup"><span data-stu-id="6d9ea-114">The identifier representing the partition from which this receiver is fetching data</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d9ea-115">受信側で構成されているプリフェッチ数を取得します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-115">Get Prefetch Count configured on the Receiver.</span></span>
            </summary>
        <value><span data-ttu-id="6d9ea-116">イベントの数の上限この受信者は受信操作が保留されているかどうかに関係なくアクティブに受信します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-116">The upper limit of events this receiver will actively receive regardless of whether a receive operation is pending.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt; ReceiveAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt;&gt; ReceiveAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;" Usage="partitionReceiver.ReceiveAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount">To be added.</param>
        <summary>
            <span data-ttu-id="6d9ea-117">受信のバッチ<see cref="T:Microsoft.Azure.EventHubs.EventData" />'s、EventHub からパーティションに分割</span><span class="sxs-lookup"><span data-stu-id="6d9ea-117">Receive a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s from an EventHub partition</span></span>
            </summary>
        <returns><span data-ttu-id="6d9ea-118">タスクのバッチを生成する<see cref="T:Microsoft.Azure.EventHubs.EventData" />この受信者を作成するパーティションから。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-118">A Task that will yield a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" /> from the partition on which this receiver is created.</span></span> <span data-ttu-id="6d9ea-119">EventData が存在しない場合、' null' を返します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-119">Returns 'null' if no EventData is present.</span></span></returns>
        <remarks>To be added.</remarks>
        <example>
            <span data-ttu-id="6d9ea-120">サンプル コード: </span><span class="sxs-lookup"><span data-stu-id="6d9ea-120">Sample code:</span></span>
            <code>
            EventHubClient client = EventHubClient.Create("__connectionString__");
            PartitionReceiver receiver = client.CreateReceiver("ConsumerGroup1", "1");
            IEnumerable&lt;EventData&gt; receivedEvents = await receiver.ReceiveAsync(BatchSize);
                 
            while (true)
            {
                int batchSize = 0;
                if (receivedEvents != null)
                {
                    foreach (EventData receivedEvent in receivedEvents)
                    {
                        Console.WriteLine("Message Payload: {0}", Encoding.UTF8.GetString(receivedEvent.Body));
                        Console.WriteLine("Offset: {0}, SeqNo: {1}, EnqueueTime: {2}", 
                            receivedEvent.SystemProperties.Offset, 
                            receivedEvent.SystemProperties.SequenceNumber, 
                            receivedEvent.SystemProperties.EnqueuedTime);
                        batchSize++;
                    }
                }
                     
                Console.WriteLine("ReceivedBatch Size: {0}", batchSize);
                receivedEvents = await receiver.ReceiveAsync();
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt; ReceiveAsync (int maxMessageCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt;&gt; ReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer, waitTime As TimeSpan) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;" Usage="partitionReceiver.ReceiveAsync (maxMessageCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.EventHubs.PartitionReceiver/&lt;ReceiveAsync&gt;d__36))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount">To be added.</param>
        <param name="waitTime">To be added.</param>
        <summary>
            <span data-ttu-id="6d9ea-121">受信のバッチ<see cref="T:Microsoft.Azure.EventHubs.EventData" />'s ごとに、待機時間を許可することで、EventHub パーティションから呼び出します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-121">Receive a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" />'s from an EventHub partition by allowing wait time on each individual call.</span></span>
            </summary>
        <returns><span data-ttu-id="6d9ea-122">タスクのバッチを生成する<see cref="T:Microsoft.Azure.EventHubs.EventData" />この受信者を作成するパーティションから。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-122">A Task that will yield a batch of <see cref="T:Microsoft.Azure.EventHubs.EventData" /> from the partition on which this receiver is created.</span></span> <span data-ttu-id="6d9ea-123">EventData が存在しない場合、' null' を返します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-123">Returns 'null' if no EventData is present.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiverRuntimeMetricEnabled">
      <MemberSignature Language="C#" Value="public bool ReceiverRuntimeMetricEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiverRuntimeMetricEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReceiverRuntimeMetricEnabled : bool" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="6d9ea-124">受信側のランタイム メトリックが有効になっているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-124">Gets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.ReceiverRuntimeInformation RuntimeInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.ReceiverRuntimeInformation RuntimeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.RuntimeInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuntimeInfo As ReceiverRuntimeInformation" />
      <MemberSignature Language="F#" Value="member this.RuntimeInfo : Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.RuntimeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.ReceiverRuntimeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d9ea-125">Event Hub の論理パーティションのランタイム情報のおおよその受信者を取得します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-125">Gets the approximate receiver runtime information for a logical partition of an Event Hub.</span></span>
            <span data-ttu-id="6d9ea-126">設定を有効にするを参照してください<see cref="T:Microsoft.Azure.EventHubs.ReceiverOptions" />と<see cref="P:Microsoft.Azure.EventHubs.EventHubClient.EnableReceiverRuntimeMetric" /></span><span class="sxs-lookup"><span data-stu-id="6d9ea-126">To enable the setting, refer to <see cref="T:Microsoft.Azure.EventHubs.ReceiverOptions" /> and <see cref="P:Microsoft.Azure.EventHubs.EventHubClient.EnableReceiverRuntimeMetric" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetReceiveHandler">
      <MemberSignature Language="C#" Value="public void SetReceiveHandler (Microsoft.Azure.EventHubs.IPartitionReceiveHandler receiveHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetReceiveHandler(class Microsoft.Azure.EventHubs.IPartitionReceiveHandler receiveHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.PartitionReceiver.SetReceiveHandler(Microsoft.Azure.EventHubs.IPartitionReceiveHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetReceiveHandler (receiveHandler As IPartitionReceiveHandler)" />
      <MemberSignature Language="F#" Value="member this.SetReceiveHandler : Microsoft.Azure.EventHubs.IPartitionReceiveHandler -&gt; unit" Usage="partitionReceiver.SetReceiveHandler receiveHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveHandler" Type="Microsoft.Azure.EventHubs.IPartitionReceiveHandler" />
      </Parameters>
      <Docs>
        <param name="receiveHandler"><span data-ttu-id="6d9ea-127"><see cref="T:Microsoft.Azure.EventHubs.IPartitionReceiveHandler" />イベントを処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-127">The <see cref="T:Microsoft.Azure.EventHubs.IPartitionReceiveHandler" /> used to process events.</span></span></param>
        <summary>
            <span data-ttu-id="6d9ea-128">セット、<see cref="T:Microsoft.Azure.EventHubs.IPartitionReceiveHandler" />イベントを処理します。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-128">Sets the <see cref="T:Microsoft.Azure.EventHubs.IPartitionReceiveHandler" /> to process events.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="protected string StartOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property StartOffset As String" />
      <MemberSignature Language="F#" Value="member this.StartOffset : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.StartOffset" />
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
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOfStream">
      <MemberSignature Language="C#" Value="public static readonly string StartOfStream;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string StartOfStream" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly StartOfStream As String " />
      <MemberSignature Language="F#" Value=" staticval mutable StartOfStream : string" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.StartOfStream" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="6d9ea-129">これは、EventHub のパーティションのストリームの開始を表すために定義された定数です。</span><span class="sxs-lookup"><span data-stu-id="6d9ea-129">This is a constant defined to represent the start of a partition stream in EventHub.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="protected Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.PartitionReceiver.StartTime" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.EventHubs.PartitionReceiver.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>