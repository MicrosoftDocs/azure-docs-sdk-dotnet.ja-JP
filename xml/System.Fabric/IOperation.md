<Type Name="IOperation" FullName="System.Fabric.IOperation">
  <TypeSignature Language="C#" Value="public interface IOperation" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IOperation" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperation" />
  <TypeSignature Language="F#" Value="type IOperation = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="dda3a-101">状態の複製物作成会社から取得されるデータをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-101">Describes the data that is obtained from the state replicator.</span></span> </para>
    </summary>
    <remarks>
      <para>
        <span data-ttu-id="dda3a-102"><see cref="T:System.Fabric.IOperation" />セカンダリ レプリカに配信される状態の変化を説明する基本インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="dda3a-102"><see cref="T:System.Fabric.IOperation" /> is the base interface that describes state changes that are delivered to a Secondary replica.</span></span> </para>
      <para>
                <span data-ttu-id="dda3a-103">含まれている、<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />とシーケンス番号およびその他の情報を識別します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-103">They contain the <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> and the sequence number and other identifying information.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Acknowledge">
      <MemberSignature Language="C#" Value="public void Acknowledge ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Acknowledge() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IOperation.Acknowledge" />
      <MemberSignature Language="VB.NET" Value="Public Sub Acknowledge ()" />
      <MemberSignature Language="F#" Value="abstract member Acknowledge : unit -&gt; unit" Usage="iOperation.Acknowledge " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="dda3a-104">この操作が、セカンダリ レプリカに正常に適用されたことを確認します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-104">Acknowledges that this operation has been successfully applied at the Secondary replica.</span></span>  </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="dda3a-105">取得するときに、サービスはこのメソッドを呼び出す必要があります、<see cref="T:System.Fabric.IOperation" />複製物作成会社と正常にローカル ストアに適用します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-105">Services should call this method when they have obtained an <see cref="T:System.Fabric.IOperation" /> from the replicator and successfully applied it to their local store.</span></span>
            <span data-ttu-id="dda3a-106">永続化されたサービスでは、このメソッドを呼び出すことが必須ため、<see cref="T:System.Fabric.FabricReplicator" />を実装するその他のオブジェクトを解放しない<see cref="T:System.Fabric.IOperation" />です。</span><span class="sxs-lookup"><span data-stu-id="dda3a-106">For persisted services, calling this method is mandatory because the <see cref="T:System.Fabric.FabricReplicator" /> does not release additional objects that implement <see cref="T:System.Fabric.IOperation" />.</span></span> <span data-ttu-id="dda3a-107">揮発性サービスでは、レプリケーターに暗黙的に承認されると operations 値の設定でそれ以外の場合は構成しない限り、受信したとき<see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" />true に設定します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-107">For volatile services, the replicator implicitly acknowledges operations when they are received unless they are configured otherwise by setting the value <see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" /> to true.</span></span>
            <span data-ttu-id="dda3a-108">プライマリ レプリカを受け取る前に、レプリカのクォーラム操作を確認する必要があります、<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />操作完了の応答。</span><span class="sxs-lookup"><span data-stu-id="dda3a-108">An operation must be acknowledged by a quorum of replicas before the Primary replica receives the <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> operation complete responses.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AtomicGroupId">
      <MemberSignature Language="C#" Value="public long AtomicGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AtomicGroupId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.AtomicGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AtomicGroupId As Long" />
      <MemberSignature Language="F#" Value="member this.AtomicGroupId : int64" Usage="System.Fabric.IOperation.AtomicGroupId" />
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
          <para><span data-ttu-id="dda3a-109">このオブジェクトを実装している場合、分割不可能なグループを識別<see cref="T:System.Fabric.IOperation" />アトミック グループの一部です。</span><span class="sxs-lookup"><span data-stu-id="dda3a-109">Identifies the atomic group, if this object that implements <see cref="T:System.Fabric.IOperation" /> is a part of an atomic group.</span></span> <span data-ttu-id="dda3a-110">分割不可能なグループはサービスがサービス グループの一部であるときにのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="dda3a-110">Atomic groups are only available when a service is a part of service group.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="dda3a-111"><see cref="T:System.Int64" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-111">Returns <see cref="T:System.Int64" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public System.Fabric.OperationData Data { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.OperationData Data" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.Data" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Data As OperationData" />
      <MemberSignature Language="F#" Value="member this.Data : System.Fabric.OperationData" Usage="System.Fabric.IOperation.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationData</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dda3a-112">取得、<see cref="T:System.Fabric.OperationData" />プライマリ レプリカによって提供されます。</span><span class="sxs-lookup"><span data-stu-id="dda3a-112">Gets the <see cref="T:System.Fabric.OperationData" /> that are provided by the Primary replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="dda3a-113"><see cref="T:System.Fabric.OperationData" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-113">Returns <see cref="T:System.Fabric.OperationData" />.</span></span></para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public System.Fabric.OperationType OperationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.OperationType OperationType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationType As OperationType" />
      <MemberSignature Language="F#" Value="member this.OperationType : System.Fabric.OperationType" Usage="System.Fabric.IOperation.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.OperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dda3a-114">この操作の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-114">Gets the type of this operation.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="dda3a-115"><see cref="T:System.Fabric.OperationType" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-115">Returns <see cref="T:System.Fabric.OperationType" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="dda3a-116"><see cref="T:System.Fabric.OperationType" />操作の種類を示します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-116">The <see cref="T:System.Fabric.OperationType" /> indicates the type of operation.</span></span> <span data-ttu-id="dda3a-117">"Normal"操作は、コピーまたはレプリケーション ストリームの一部としてグループ化のサービスによって送信されるこれらの操作です。</span><span class="sxs-lookup"><span data-stu-id="dda3a-117">"Normal" operations are those operations that are sent by non-service grouped services as part of either the copy or replication streams.</span></span> <span data-ttu-id="dda3a-118">その他の種類の操作は、サービス グループに固有の管理操作を表します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-118">Other types of operations represent control operations that are specific to service groups.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IOperation.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="System.Fabric.IOperation.SequenceNumber" />
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
          <para><span data-ttu-id="dda3a-119">この操作のシーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-119">Gets the sequence number of this operation.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="dda3a-120"><see cref="T:System.Int64" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="dda3a-120">Returns <see cref="T:System.Int64" />.</span></span></para>
        </value>
        <remarks>
          <para>
                <span data-ttu-id="dda3a-121">シーケンス番号がの一部として提供される、<see cref="P:System.Fabric.IOperation.SequenceNumber" /></span><span class="sxs-lookup"><span data-stu-id="dda3a-121">The sequence number is provided as a part of the <see cref="P:System.Fabric.IOperation.SequenceNumber" /></span></span></para>
          <para>
                <span data-ttu-id="dda3a-122">レプリケーションのストリームから受信した操作 (<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />) からは、プライマリ レプリカを受信すると、同じシーケンス番号は<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="dda3a-122">For operations received from the replication stream (<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />) the sequence number is the same that the Primary replica that are receives from <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" /> method.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>