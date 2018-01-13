<Type Name="Checkpoint" FullName="Microsoft.Azure.EventHubs.Processor.Checkpoint">
  <TypeSignature Language="C#" Value="public class Checkpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Checkpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.Checkpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class Checkpoint" />
  <TypeSignature Language="F#" Value="type Checkpoint = class" />
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
            <span data-ttu-id="05fc1-101">ストリームの状態を維持するために使用するコンテキスト オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="05fc1-101">The context object used to preserve state in the stream.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Checkpoint (Microsoft.Azure.EventHubs.Processor.Checkpoint source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.EventHubs.Processor.Checkpoint source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.Checkpoint.#ctor(Microsoft.Azure.EventHubs.Processor.Checkpoint)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As Checkpoint)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.Checkpoint : Microsoft.Azure.EventHubs.Processor.Checkpoint -&gt; Microsoft.Azure.EventHubs.Processor.Checkpoint" Usage="new Microsoft.Azure.EventHubs.Processor.Checkpoint source" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.EventHubs.Processor.Checkpoint" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="05fc1-102">コピーする既存のチェックポイント</span><span class="sxs-lookup"><span data-stu-id="05fc1-102">The existing checkpoint to copy</span></span></param>
        <summary>
            <span data-ttu-id="05fc1-103">既存のチェックポイントから、新しいチェックポイントを作成します。</span><span class="sxs-lookup"><span data-stu-id="05fc1-103">Creates a new Checkpoint from an existing checkpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Checkpoint (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.Checkpoint.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.Checkpoint : string -&gt; Microsoft.Azure.EventHubs.Processor.Checkpoint" Usage="new Microsoft.Azure.EventHubs.Processor.Checkpoint partitionId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="05fc1-104">チェックポイントのパーティション ID</span><span class="sxs-lookup"><span data-stu-id="05fc1-104">The partition ID for the checkpoint</span></span></param>
        <summary>
            <span data-ttu-id="05fc1-105">特定のパーティション ID 用に新しいチェックポイントを作成します。</span><span class="sxs-lookup"><span data-stu-id="05fc1-105">Creates a new Checkpoint for a particular partition ID.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Checkpoint (string partitionId, string offset, long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionId, string offset, int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.Checkpoint.#ctor(System.String,System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionId As String, offset As String, sequenceNumber As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.Checkpoint : string * string * int64 -&gt; Microsoft.Azure.EventHubs.Processor.Checkpoint" Usage="new Microsoft.Azure.EventHubs.Processor.Checkpoint (partitionId, offset, sequenceNumber)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="offset" Type="System.String" />
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="05fc1-106">チェックポイントのパーティション ID</span><span class="sxs-lookup"><span data-stu-id="05fc1-106">The partition ID for the checkpoint</span></span></param>
        <param name="offset"><span data-ttu-id="05fc1-107">最後のオフセットの処理<see cref="T:Microsoft.Azure.EventHubs.EventData" /></span><span class="sxs-lookup"><span data-stu-id="05fc1-107">The offset for the last processed <see cref="T:Microsoft.Azure.EventHubs.EventData" /></span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="05fc1-108">最後のシーケンス番号の処理<see cref="T:Microsoft.Azure.EventHubs.EventData" /></span><span class="sxs-lookup"><span data-stu-id="05fc1-108">The sequence number of the last processed <see cref="T:Microsoft.Azure.EventHubs.EventData" /></span></span></param>
        <summary>
            <span data-ttu-id="05fc1-109">特定のパーティション ID に、オフセットやシーケンス番号を用に新しいチェックポイントを作成します。</span><span class="sxs-lookup"><span data-stu-id="05fc1-109">Creates a new Checkpoint for a particular partition ID, with the offset and sequence number.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Checkpoint.Offset" />
      <MemberSignature Language="VB.NET" Value="Public Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string with get, set" Usage="Microsoft.Azure.EventHubs.Processor.Checkpoint.Offset" />
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
            <span data-ttu-id="05fc1-110">最後のオフセットを取得または処理<see cref="T:Microsoft.Azure.EventHubs.EventData" />です。</span><span class="sxs-lookup"><span data-stu-id="05fc1-110">Gets or sets the offset of the last processed <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Checkpoint.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.Azure.EventHubs.Processor.Checkpoint.PartitionId" />
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
            <span data-ttu-id="05fc1-111">対応するチェックポイントのパーティション ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="05fc1-111">Gets the partition ID for the corresponding checkpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Checkpoint.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64 with get, set" Usage="Microsoft.Azure.EventHubs.Processor.Checkpoint.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="05fc1-112">最後のシーケンス番号の設定を取得または処理<see cref="T:Microsoft.Azure.EventHubs.EventData" />です。</span><span class="sxs-lookup"><span data-stu-id="05fc1-112">Gets or sets the sequence number of the last processed <see cref="T:Microsoft.Azure.EventHubs.EventData" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>