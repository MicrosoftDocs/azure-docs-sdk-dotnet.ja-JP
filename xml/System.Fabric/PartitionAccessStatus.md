<Type Name="PartitionAccessStatus" FullName="System.Fabric.PartitionAccessStatus">
  <TypeSignature Language="C#" Value="public enum PartitionAccessStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PartitionAccessStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PartitionAccessStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum PartitionAccessStatus" />
  <TypeSignature Language="F#" Value="type PartitionAccessStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="1e5f1-101">パーティションのアクセスの状態を列挙します。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-101">Enumerates the access status of the partition.</span></span> </para>
    </summary>
    <remarks>
      <para>
        <span data-ttu-id="1e5f1-102"><see cref="T:System.Fabric.PartitionAccessStatus" />読み取りまたは書き込み操作が許可されていること確認に使用されます。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-102"><see cref="T:System.Fabric.PartitionAccessStatus" /> is used to check that a read or write operation is allowed.</span></span> <span data-ttu-id="1e5f1-103">サービス レプリカでは、クライアント要求を処理するときに、システムが、処理を許可する状態を確認します。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-103">When service replicas handle a client request, they should verify that the system is in a state that allows processing.</span></span> <span data-ttu-id="1e5f1-104">チェックして、<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />または<see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" />を適切な操作を妨げる条件の必要に応じて、レプリカを通知することができます。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-104">By checking the <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" /> or <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> as appropriate, the replica can be notified of conditions that prevent correct operation.</span></span> <span data-ttu-id="1e5f1-105">書き込み操作を可能性がありますも例外を参照して、これらの条件のいずれかの複製物作成会社からの間で変わる可能性がある条件、<see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" />チェックとへの呼び出し<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />です。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-105">Note that write operations might still see an exception from the replicator for one of these conditions, because the condition might change between the <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> check and the call to <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />.</span></span> </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Granted">
      <MemberSignature Language="C#" Value="Granted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus Granted = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.Granted" />
      <MemberSignature Language="VB.NET" Value="Granted" />
      <MemberSignature Language="F#" Value="Granted = 1" Usage="System.Fabric.PartitionAccessStatus.Granted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1e5f1-106">読み取りまたは書き込み操作のアクセスが許可される操作が許可されていることを示します。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-106">Indicates that the read or write operation access is granted and the operation is allowed.</span></span> </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.PartitionAccessStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1e5f1-107">読み取りまたは書き込み操作のアクセスの状態が無効であることを示します。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-107">Indicates that the read or write operation access status is not valid.</span></span> <span data-ttu-id="1e5f1-108">この値は、呼び出し元に返されません。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-108">This value is not returned to the caller.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NotPrimary">
      <MemberSignature Language="C#" Value="NotPrimary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus NotPrimary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.NotPrimary" />
      <MemberSignature Language="VB.NET" Value="NotPrimary" />
      <MemberSignature Language="F#" Value="NotPrimary = 3" Usage="System.Fabric.PartitionAccessStatus.NotPrimary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1e5f1-109">このクライアント要求がプライマリ レプリカではないレプリカによって受信されたことを示します。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-109">Indicates that this client request was received by a replica that is not a Primary replica.</span></span> <span data-ttu-id="1e5f1-110">このレプリカでは、読み取りまたは書き込み操作を実行できません。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-110">The read or write operation cannot be performed at this replica.</span></span> <span data-ttu-id="1e5f1-111">クライアントは、名前付けサービスを使用して正しいプライマリ レプリカを特定しようとする必要があります。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-111">The client should attempt to use the naming service to identify the correct primary replica.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NoWriteQuorum">
      <MemberSignature Language="C#" Value="NoWriteQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus NoWriteQuorum = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.NoWriteQuorum" />
      <MemberSignature Language="VB.NET" Value="NoWriteQuorum" />
      <MemberSignature Language="F#" Value="NoWriteQuorum = 4" Usage="System.Fabric.PartitionAccessStatus.NoWriteQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1e5f1-112">使用できる書き込みクォーラムがないと、そのため、書き込み操作が受け入れられませんことを示します。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-112">Indicates that no write quorum is available and, therefore, no write operation can be accepted.</span></span> <span data-ttu-id="1e5f1-113">クライアントは、このレプリカで操作を再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-113">The client should retry the operation at this replica.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationPending">
      <MemberSignature Language="C#" Value="ReconfigurationPending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus ReconfigurationPending = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.ReconfigurationPending" />
      <MemberSignature Language="VB.NET" Value="ReconfigurationPending" />
      <MemberSignature Language="F#" Value="ReconfigurationPending = 2" Usage="System.Fabric.PartitionAccessStatus.ReconfigurationPending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1e5f1-114">再構成が進行中のために、クライアントが、後でもう一度試行する必要がありますを示します。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-114">Indicates that the client should try again later, because a reconfiguration is in progress.</span></span> <span data-ttu-id="1e5f1-115">再構成が完了すると、さらに手順を説明する新しい状態が返されます。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-115">After the reconfiguration is completed, a new status is returned that gives further instructions.</span></span> <span data-ttu-id="1e5f1-116">クライアントは、このレプリカで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="1e5f1-116">The client should retry the operation at this replica</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>