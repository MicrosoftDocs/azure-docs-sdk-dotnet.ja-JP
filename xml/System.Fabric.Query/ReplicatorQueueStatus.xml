<Type Name="ReplicatorQueueStatus" FullName="System.Fabric.Query.ReplicatorQueueStatus">
  <TypeSignature Language="C#" Value="public sealed class ReplicatorQueueStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicatorQueueStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ReplicatorQueueStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicatorQueueStatus" />
  <TypeSignature Language="F#" Value="type ReplicatorQueueStatus = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="09ad8-101">Service Fabric レプリケーターに使用するキューのさまざまな統計情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-101">Provides various statistics of the queue used in the Service Fabric Replicator.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="09ad8-102">レプリケーターの役割によって (<see cref="F:System.Fabric.ReplicaRole.Primary" />または<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />)、この型のプロパティが異なる状況を意味します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-102">Depending on the role of the replicator (<see cref="F:System.Fabric.ReplicaRole.Primary" /> or <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />), the properties in this type mean different things.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicatorQueueStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ReplicatorQueueStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="09ad8-103"><see cref="T:System.Fabric.Query.ReplicatorQueueStatus" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-103">Initializes a new instance of the <see cref="T:System.Fabric.Query.ReplicatorQueueStatus" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommittedSequenceNumber">
      <MemberSignature Language="C#" Value="public long CommittedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CommittedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.CommittedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CommittedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CommittedSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.CommittedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="09ad8-104">「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="09ad8-104">See remarks.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="09ad8-105">コミットされたシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="09ad8-105">The committed sequence number.</span></span></para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <span data-ttu-id="09ad8-106"><see cref="F:System.Fabric.ReplicaRole.Primary" />– を一番大きいシーケンス番号を表す、<b>クォーラム</b>のセカンダリ レプリカが、操作を適用します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-106"><see cref="F:System.Fabric.ReplicaRole.Primary" /> – Represents the highest sequence number for which a <b>quorum</b> of secondary replicas have applied the operation.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <span data-ttu-id="09ad8-107"><see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– プライマリからセカンダリにレプリケーターによって受信されたが最大のシーケンス番号を表します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-107"><see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> – Represents the highest sequence number that has been received by the secondary replicator from the primary.</span></span></para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompletedSequenceNumber">
      <MemberSignature Language="C#" Value="public long CompletedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CompletedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.CompletedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompletedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CompletedSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.CompletedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="09ad8-108">「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="09ad8-108">See remarks.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="09ad8-109">完了したシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="09ad8-109">The completed sequence number.</span></span></para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <span data-ttu-id="09ad8-110"><see cref="F:System.Fabric.ReplicaRole.Primary" />– を一番大きいシーケンス番号を表す<b>すべて</b>セカンダリ レプリカが、操作を適用します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-110"><see cref="F:System.Fabric.ReplicaRole.Primary" /> – Represents the highest sequence number for which <b>all</b> the secondary replicas have applied the operation.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <span data-ttu-id="09ad8-111"><see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– ユーザーのサービスのレプリカによって適用されている最大のシーケンス番号を表します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-111"><see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> – Represents the highest sequence number that has been applied by the user service replica.</span></span></para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FirstSequenceNumber">
      <MemberSignature Language="C#" Value="public long FirstSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FirstSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.FirstSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FirstSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.FirstSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.FirstSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="09ad8-112">「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="09ad8-112">See remarks.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="09ad8-113">最初のシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="09ad8-113">The first sequence number.</span></span></para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <span data-ttu-id="09ad8-114"><see cref="F:System.Fabric.ReplicaRole.Primary" />– キューに存在する操作の最小値のシーケンス番号を表します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-114"><see cref="F:System.Fabric.ReplicaRole.Primary" /> – Represents the smallest sequence number of the operation that is present in the queue.</span></span> <span data-ttu-id="09ad8-115">値は同じになります<see cref="P:System.Fabric.Query.ReplicatorQueueStatus.CompletedSequenceNumber" />、すべてのセカンダリ レプリカから受信確認を受信した後、プライマリのレプリケーターが操作を破棄します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-115">It’s value will be the same as <see cref="P:System.Fabric.Query.ReplicatorQueueStatus.CompletedSequenceNumber" />, since the primary replicator discards operations once it receives an acknowledgement from all the secondary replicas.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <span data-ttu-id="09ad8-116"><see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– キューで利用可能な最初の操作のシーケンス番号を表します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-116"><see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> – Represents the sequence number of the first operation that is available in the queue.</span></span></para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.LastSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.LastSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="09ad8-117">「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="09ad8-117">See remarks.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="09ad8-118">最後のシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="09ad8-118">The last sequence number.</span></span></para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <span data-ttu-id="09ad8-119"><see cref="F:System.Fabric.ReplicaRole.Primary" />– キューで提供される操作の最後のシーケンス番号を表します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-119"><see cref="F:System.Fabric.ReplicaRole.Primary" /> – Represents the latest sequence number of the operation that is available in the queue.</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <span data-ttu-id="09ad8-120"><see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– キューで提供される操作の最後のシーケンス番号を表します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-120"><see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> – Represents the latest sequence number of the operation that is available in the queue.</span></span></para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueMemorySize">
      <MemberSignature Language="C#" Value="public long QueueMemorySize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 QueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.QueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueMemorySize As Long" />
      <MemberSignature Language="F#" Value="member this.QueueMemorySize : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.QueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="09ad8-121">キューが使用されている仮想メモリ バイト数を取得します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-121">Gets the number of virtual memory bytes being consumed by the queue.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="09ad8-122">キューが使用されている仮想メモリ バイト数。</span><span class="sxs-lookup"><span data-stu-id="09ad8-122">The number of virtual memory bytes being consumed by the queue.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueUtilizationPercentage">
      <MemberSignature Language="C#" Value="public long QueueUtilizationPercentage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 QueueUtilizationPercentage" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.QueueUtilizationPercentage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueUtilizationPercentage As Long" />
      <MemberSignature Language="F#" Value="member this.QueueUtilizationPercentage : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.QueueUtilizationPercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="09ad8-123">キューの使用率を取得します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-123">Gets the utilization of the queue.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="09ad8-124">キューの使用率。</span><span class="sxs-lookup"><span data-stu-id="09ad8-124">The utilization of the queue.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="09ad8-125">値が '0' のことを示し、キューが空 '100' の値は、キューがいっぱいであることを示します。</span><span class="sxs-lookup"><span data-stu-id="09ad8-125">A value of ‘0’ indicates that the queue is empty and a value of ‘100’ indicates that the queue is full.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>