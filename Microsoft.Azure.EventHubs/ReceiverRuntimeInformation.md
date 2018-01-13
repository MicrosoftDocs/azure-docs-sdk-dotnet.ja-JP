<Type Name="ReceiverRuntimeInformation" FullName="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation">
  <TypeSignature Language="C#" Value="public class ReceiverRuntimeInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReceiverRuntimeInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class ReceiverRuntimeInformation" />
  <TypeSignature Language="F#" Value="type ReceiverRuntimeInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="899e9-101">Event Hub の論理パーティションのおおよそのレシーバー ランタイム情報を表します。</span><span class="sxs-lookup"><span data-stu-id="899e9-101">Represents the approximate receiver runtime information for a logical partition of an Event Hub.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LastEnqueuedOffset">
      <MemberSignature Language="C#" Value="public string LastEnqueuedOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastEnqueuedOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastEnqueuedOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedOffset As String" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedOffset : string" Usage="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastEnqueuedOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="899e9-102">最後にエンキューされたイベントのオフセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="899e9-102">Gets the offset of the last enqueued event.</span></span></summary>
        <value><span data-ttu-id="899e9-103">最後のエンキューされたイベントのオフセット。</span><span class="sxs-lookup"><span data-stu-id="899e9-103">The offset of the last enqueued event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastEnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastEnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastEnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastEnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedTimeUtc : DateTime" Usage="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastEnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="899e9-104">最後のイベントのエンキューされた UTC 時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="899e9-104">Gets the enqueued UTC time of the last event.</span></span></summary>
        <value><span data-ttu-id="899e9-105">最後のイベントのエンキューされた時刻。</span><span class="sxs-lookup"><span data-stu-id="899e9-105">The enqueued time of the last event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastSequenceNumber : int64" Usage="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.LastSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="899e9-106">Event Hub のパーティションのストリーム内のイベントの最後のシーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="899e9-106">Gets the last sequence number of the event within the partition stream of the Event Hub.</span></span></summary>
        <value><span data-ttu-id="899e9-107">イベントの論理シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="899e9-107">The logical sequence number of the event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="899e9-108">Event Hub の論理パーティションのパーティション ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="899e9-108">Gets the partition ID for a logical partition of an Event Hub.</span></span></summary>
        <value><span data-ttu-id="899e9-109">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="899e9-109">The partition identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrievalTime">
      <MemberSignature Language="C#" Value="public DateTime RetrievalTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime RetrievalTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.RetrievalTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetrievalTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.RetrievalTime : DateTime" Usage="Microsoft.Azure.EventHubs.ReceiverRuntimeInformation.RetrievalTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="899e9-110">ランタイム情報が取得された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="899e9-110">Gets the time of when the runtime info was retrieved.</span></span></summary>
        <value><span data-ttu-id="899e9-111">最後のイベントのエンキューされた時刻。</span><span class="sxs-lookup"><span data-stu-id="899e9-111">The enqueued time of the last event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>