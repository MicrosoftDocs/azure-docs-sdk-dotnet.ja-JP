<Type Name="EventData+SystemPropertiesCollection" FullName="Microsoft.Azure.EventHubs.EventData+SystemPropertiesCollection">
  <TypeSignature Language="C#" Value="public sealed class EventData.SystemPropertiesCollection" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit EventData/SystemPropertiesCollection extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventData.SystemPropertiesCollection" />
  <TypeSignature Language="F#" Value="type EventData.SystemPropertiesCollection = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6e78f-101">Event Hubs サービスによって設定されるプロパティの保存に使用されるコレクション。</span><span class="sxs-lookup"><span data-stu-id="6e78f-101">A collection used to store properties which are set by the Event Hubs service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e78f-102">取得または送信時刻の日時を UTC に設定します。</span><span class="sxs-lookup"><span data-stu-id="6e78f-102">Gets or sets the date and time of the sent time in UTC.</span></span></summary>
        <value><span data-ttu-id="6e78f-103">エンキュー刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="6e78f-103">The enqueue time in UTC.</span></span> <span data-ttu-id="6e78f-104">この値は、メッセージをエンキューの実際の時間を表します。</span><span class="sxs-lookup"><span data-stu-id="6e78f-104">This value represents the actual time of enqueuing the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.Offset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string" Usage="Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.Offset" />
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
            <span data-ttu-id="6e78f-105">イベント ハブ パーティション ストリームに対して相対的には、データのオフセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="6e78f-105">Gets the offset of the data relative to the Event Hub partition stream.</span></span> <span data-ttu-id="6e78f-106">オフセットは、マーカーまたは Event Hubs ストリーム内のイベントの識別子です。</span><span class="sxs-lookup"><span data-stu-id="6e78f-106">The offset is a marker or identifier for an event within the Event Hubs stream.</span></span> <span data-ttu-id="6e78f-107">識別子は、Event Hubs ストリームのパーティション内で一意です。</span><span class="sxs-lookup"><span data-stu-id="6e78f-107">The identifier is unique within a partition of the Event Hubs stream.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string" Usage="Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.PartitionKey" />
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
        <summary><span data-ttu-id="6e78f-108">格納されている、対応するパーティションのパーティション キーを取得します<see cref="T:Microsoft.Azure.EventHubs.EventData" /></span><span class="sxs-lookup"><span data-stu-id="6e78f-108">Gets the partition key of the corresponding partition that stored the <see cref="T:Microsoft.Azure.EventHubs.EventData" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.Azure.EventHubs.EventData.SystemPropertiesCollection.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6e78f-109">Event Hub のパーティションのストリーム内のイベントの論理シーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e78f-109">Gets the logical sequence number of the event within the partition stream of the Event Hub.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>