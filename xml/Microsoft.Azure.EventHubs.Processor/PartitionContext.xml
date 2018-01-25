<Type Name="PartitionContext" FullName="Microsoft.Azure.EventHubs.Processor.PartitionContext">
  <TypeSignature Language="C#" Value="public class PartitionContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.PartitionContext" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionContext" />
  <TypeSignature Language="F#" Value="type PartitionContext = class" />
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
            <span data-ttu-id="9d4a8-101">によって使用されるイベント ハブ パーティションに関連する情報をカプセル化<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="9d4a8-101">Encapsulates information related to an Event Hubs partition used by <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CheckpointAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CheckpointAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.PartitionContext.CheckpointAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CheckpointAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CheckpointAsync : unit -&gt; System.Threading.Tasks.Task" Usage="partitionContext.CheckpointAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d4a8-102">チェックポイント マネージャーを使用してチェックポイント ストアに、現在のオフセットと sequenceNumber を書き込みます。</span><span class="sxs-lookup"><span data-stu-id="9d4a8-102">Writes the current offset and sequenceNumber to the checkpoint store via the checkpoint manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CheckpointAsync (Microsoft.Azure.EventHubs.EventData eventData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CheckpointAsync(class Microsoft.Azure.EventHubs.EventData eventData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.PartitionContext.CheckpointAsync(Microsoft.Azure.EventHubs.EventData)" />
      <MemberSignature Language="F#" Value="member this.CheckpointAsync : Microsoft.Azure.EventHubs.EventData -&gt; System.Threading.Tasks.Task" Usage="partitionContext.CheckpointAsync eventData" />
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
        <Parameter Name="eventData" Type="Microsoft.Azure.EventHubs.EventData" />
      </Parameters>
      <Docs>
        <param name="eventData"><span data-ttu-id="9d4a8-103">有効なオフセットと sequenceNumber 受信 EventData</span><span class="sxs-lookup"><span data-stu-id="9d4a8-103">A received EventData with valid offset and sequenceNumber</span></span></param>
        <summary>
            <span data-ttu-id="9d4a8-104">オフセットと指定された受信 EventData インスタンスから sequenceNumber を保存し、チェックポイント マネージャーを使用してチェックポイント ストアにこれらの値を書き込みます。</span><span class="sxs-lookup"><span data-stu-id="9d4a8-104">Stores the offset and sequenceNumber from the provided received EventData instance, then writes those values to the checkpoint store via the checkpoint manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="9d4a8-105">指定の eventData が null の場合</span><span class="sxs-lookup"><span data-stu-id="9d4a8-105">If suplied eventData is null</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="9d4a8-106">場合、sequenceNumber は最後のチェックポイントが設定された値より小さい</span><span class="sxs-lookup"><span data-stu-id="9d4a8-106">If the sequenceNumber is less than the last checkpointed value</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionContext.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string" Usage="Microsoft.Azure.EventHubs.Processor.PartitionContext.ConsumerGroupName" />
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
            <span data-ttu-id="9d4a8-107">コンシューマー グループの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d4a8-107">Gets the name of the consumer group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionContext.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.Azure.EventHubs.Processor.PartitionContext.EventHubPath" />
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
            <span data-ttu-id="9d4a8-108">イベント ハブのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9d4a8-108">Gets the path of the event hub.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owner">
      <MemberSignature Language="C#" Value="public string Owner { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Owner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionContext.Owner" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Owner As String" />
      <MemberSignature Language="F#" Value="member this.Owner : string" Usage="Microsoft.Azure.EventHubs.Processor.PartitionContext.Owner" />
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
            <span data-ttu-id="9d4a8-109">パーティションのホスト所有者を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d4a8-109">Gets the host owner for the partition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionContext.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.Processor.PartitionContext.PartitionId" />
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
            <span data-ttu-id="9d4a8-110">コンテキストのパーティション ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d4a8-110">Gets the partition ID for the context.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.ReceiverRuntimeInformation RuntimeInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.EventHubs.ReceiverRuntimeInformation RuntimeInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionContext.RuntimeInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuntimeInformation As ReceiverRuntimeInformation" />
      <MemberSignature Language="F#" Value="member this.RuntimeInformation : Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" Usage="Microsoft.Azure.EventHubs.Processor.PartitionContext.RuntimeInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.ReceiverRuntimeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d4a8-111">Event Hub の論理パーティションのランタイム情報のおおよその受信者を取得します。</span><span class="sxs-lookup"><span data-stu-id="9d4a8-111">Gets the approximate receiver runtime information for a logical partition of an Event Hub.</span></span>
            <span data-ttu-id="9d4a8-112">設定を有効にするを参照してください。<see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.EnableReceiverRuntimeMetric" /></span><span class="sxs-lookup"><span data-stu-id="9d4a8-112">To enable the setting, refer to <see cref="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.EnableReceiverRuntimeMetric" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.PartitionContext.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionContext.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d4a8-113">次の format:"PartitionContext({EventHubPath}/{ConsumerGroupName}/{PartitionId}/{SequenceNumber}) でパーティション コンテキストを提供します"</span><span class="sxs-lookup"><span data-stu-id="9d4a8-113">Provides the parition context in the following format:"PartitionContext({EventHubPath}/{ConsumerGroupName}/{PartitionId}/{SequenceNumber})"</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>