<Type Name="Lease" FullName="Microsoft.Azure.EventHubs.Processor.Lease">
  <TypeSignature Language="C#" Value="public class Lease" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Lease extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.Lease" />
  <TypeSignature Language="VB.NET" Value="Public Class Lease" />
  <TypeSignature Language="F#" Value="type Lease = class" />
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
            <span data-ttu-id="749a7-101">パーティションの所有権情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="749a7-101">Contains partition ownership information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Lease ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.Lease.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Lease (Microsoft.Azure.EventHubs.Processor.Lease source);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.EventHubs.Processor.Lease source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.Lease.#ctor(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (source As Lease)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.Lease : Microsoft.Azure.EventHubs.Processor.Lease -&gt; Microsoft.Azure.EventHubs.Processor.Lease" Usage="new Microsoft.Azure.EventHubs.Processor.Lease source" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="source"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Lease (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.Lease.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (partitionId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.Processor.Lease : string -&gt; Microsoft.Azure.EventHubs.Processor.Lease" Usage="new Microsoft.Azure.EventHubs.Processor.Lease partitionId" />
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
        <param name="partitionId"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public long Epoch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Lease.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public Property Epoch As Long" />
      <MemberSignature Language="F#" Value="member this.Epoch : int64 with get, set" Usage="Microsoft.Azure.EventHubs.Processor.Lease.Epoch" />
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
            <span data-ttu-id="749a7-102">取得または競合するノードの間でパーティションの最新の所有者を特定する使用できる値は、リースのエポック年を設定します。</span><span class="sxs-lookup"><span data-stu-id="749a7-102">Gets or sets the epoch year of the lease, which is a value you can use to determine the most recent owner of a partition between competing nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExpired">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; IsExpired ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; IsExpired() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.Lease.IsExpired" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsExpired () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member IsExpired : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.IsExpired : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="lease.IsExpired " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="749a7-103">リースの期限が切れているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="749a7-103">Determines whether the lease is expired.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Lease.Offset" />
      <MemberSignature Language="VB.NET" Value="Public Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string with get, set" Usage="Microsoft.Azure.EventHubs.Processor.Lease.Offset" />
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
            <span data-ttu-id="749a7-104">取得またはストリーム内のオフセットの現在の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="749a7-104">Gets or sets the current value for the offset in the stream.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owner">
      <MemberSignature Language="C#" Value="public string Owner { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Owner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Lease.Owner" />
      <MemberSignature Language="VB.NET" Value="Public Property Owner As String" />
      <MemberSignature Language="F#" Value="member this.Owner : string with get, set" Usage="Microsoft.Azure.EventHubs.Processor.Lease.Owner" />
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
            <span data-ttu-id="749a7-105">取得またはパーティションのホスト所有者を設定します。</span><span class="sxs-lookup"><span data-stu-id="749a7-105">Gets or sets the host owner for the partition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Lease.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string with get, set" Usage="Microsoft.Azure.EventHubs.Processor.Lease.PartitionId" />
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
            <span data-ttu-id="749a7-106">このリースが属しているパーティションの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="749a7-106">Gets the ID of the partition to which this lease belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Lease.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64 with get, set" Usage="Microsoft.Azure.EventHubs.Processor.Lease.SequenceNumber" />
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
            <span data-ttu-id="749a7-107">取得またはストリームの最後のチェックポイントが設定されたシーケンス番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="749a7-107">Gets or sets the last checkpointed sequence number in the stream.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.Lease.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.Azure.EventHubs.Processor.Lease.Token" />
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
            <span data-ttu-id="749a7-108">取得またはホスト間で同時に管理リース トークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="749a7-108">Gets or sets the lease token that manages concurrency between hosts.</span></span> <span data-ttu-id="749a7-109">必要なすべてのリソースへの単一のアクセスを保証するためにこのトークンを使用することができます、<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="749a7-109">You can use this token to guarantee single access to any resource needed by the <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>