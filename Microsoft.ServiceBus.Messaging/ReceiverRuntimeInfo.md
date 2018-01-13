<Type Name="ReceiverRuntimeInfo" FullName="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo">
  <TypeSignature Language="C#" Value="public class ReceiverRuntimeInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReceiverRuntimeInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ReceiverRuntimeInfo" />
  <TypeSignature Language="F#" Value="type ReceiverRuntimeInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="b9495-101">Event Hub の論理パーティションのおおよそのレシーバー ランタイム情報を表します。</span><span class="sxs-lookup"><span data-stu-id="b9495-101">Represents the approximate receiver runtime information for a logical partition of an Event Hub.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReceiverRuntimeInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastEnqueuedOffset">
      <MemberSignature Language="C#" Value="public string LastEnqueuedOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastEnqueuedOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastEnqueuedOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedOffset As String" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedOffset : string" Usage="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastEnqueuedOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b9495-102">最後にエンキューされたイベントのオフセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="b9495-102">Gets the offset of the last enqueued event.</span></span></summary>
        <value><span data-ttu-id="b9495-103">最後のエンキューされたイベントのオフセット。</span><span class="sxs-lookup"><span data-stu-id="b9495-103">The offset of the last enqueued event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastEnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastEnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastEnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastEnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastEnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastEnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastEnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b9495-104">最後のイベントのエンキューされた UTC 時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="b9495-104">Gets the enqueued UTC time of the last event.</span></span></summary>
        <value><span data-ttu-id="b9495-105">最後のイベントのエンキューされた時刻。</span><span class="sxs-lookup"><span data-stu-id="b9495-105">The enqueued time of the last event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.LastSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b9495-106">Event Hub のパーティションのストリーム内のイベントの最後のシーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="b9495-106">Gets the last sequence number of the event within the partition stream of the Event Hub.</span></span></summary>
        <value><span data-ttu-id="b9495-107">イベントの論理シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="b9495-107">The logical sequence number of the event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b9495-108">Event Hub の論理パーティションのパーティション ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="b9495-108">Gets the partition ID for a logical partition of an Event Hub.</span></span></summary>
        <value><span data-ttu-id="b9495-109">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="b9495-109">The partition identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrievalTime">
      <MemberSignature Language="C#" Value="public DateTime RetrievalTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime RetrievalTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.RetrievalTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetrievalTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.RetrievalTime : DateTime" Usage="Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo.RetrievalTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="b9495-110">ランタイム情報が取得された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="b9495-110">Gets the time of when the runtime info was retrieved.</span></span></summary>
        <value><span data-ttu-id="b9495-111">最後のイベントのエンキューされた時刻。</span><span class="sxs-lookup"><span data-stu-id="b9495-111">The enqueued time of the last event.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>