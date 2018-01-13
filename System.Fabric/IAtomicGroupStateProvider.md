<Type Name="IAtomicGroupStateProvider" FullName="System.Fabric.IAtomicGroupStateProvider">
  <TypeSignature Language="C#" Value="public interface IAtomicGroupStateProvider : System.Fabric.IStateProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAtomicGroupStateProvider implements class System.Fabric.IStateProvider" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IAtomicGroupStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAtomicGroupStateProvider&#xA;Implements IStateProvider" />
  <TypeSignature Language="F#" Value="type IAtomicGroupStateProvider = interface&#xA;    interface IStateProvider" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IStateProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="4508d-101">その他の方法について説明します、<see cref="T:System.Fabric.IAtomicGroupStateProvider" />インターフェイス ユーザー サービスがサービス グループのアトミック グループ機能を活用するために実装する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4508d-101">Describes additional methods of the <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> interface that a user service must implement to take advantage of the atomic group functionality of a service group.</span></span> </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AtomicGroupCommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AtomicGroupCommitAsync (long atomicGroupId, long commitSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AtomicGroupCommitAsync(int64 atomicGroupId, int64 commitSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupCommitAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AtomicGroupCommitAsync : int64 * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAtomicGroupStateProvider.AtomicGroupCommitAsync (atomicGroupId, commitSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="commitSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para><span data-ttu-id="4508d-102">コミットするグループの ID。</span><span class="sxs-lookup"><span data-stu-id="4508d-102">The ID of the group to be committed.</span></span></para>
        </param>
        <param name="commitSequenceNumber">
          <para><span data-ttu-id="4508d-103">コミット操作のシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4508d-103">The sequence number for the commit operation.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4508d-104"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4508d-104">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="4508d-105">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4508d-105">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4508d-106">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4508d-106">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4508d-107">特定のアトミックなグループをコミットします。</span><span class="sxs-lookup"><span data-stu-id="4508d-107">Commits a particular atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4508d-108"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="4508d-108">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AtomicGroupRollbackAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AtomicGroupRollbackAsync (long atomicGroupId, long rollbackSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AtomicGroupRollbackAsync(int64 atomicGroupId, int64 rollbackSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupRollbackAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AtomicGroupRollbackAsync : int64 * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAtomicGroupStateProvider.AtomicGroupRollbackAsync (atomicGroupId, rollbackSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="rollbackSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para><span data-ttu-id="4508d-109">ロールバックするグループの ID。</span><span class="sxs-lookup"><span data-stu-id="4508d-109">The ID of the group to roll back.</span></span></para>
        </param>
        <param name="rollbackSequenceNumber">
          <para><span data-ttu-id="4508d-110">ロールバック操作のシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4508d-110">The sequence number for the rollback operation.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4508d-111"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4508d-111">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="4508d-112">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4508d-112">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4508d-113">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4508d-113">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4508d-114">特定のアトミックなグループをロールバックします。</span><span class="sxs-lookup"><span data-stu-id="4508d-114">Rolls back a particular atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="4508d-115"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="4508d-115">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AtomicGroupUndoProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AtomicGroupUndoProgressAsync (long fromCommitSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AtomicGroupUndoProgressAsync(int64 fromCommitSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupUndoProgressAsync(System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AtomicGroupUndoProgressAsync : int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAtomicGroupStateProvider.AtomicGroupUndoProgressAsync (fromCommitSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromCommitSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="fromCommitSequenceNumber">
          <para><span data-ttu-id="4508d-116">コミット操作の LSN。</span><span class="sxs-lookup"><span data-stu-id="4508d-116">The LSN of a commit operation.</span></span> <span data-ttu-id="4508d-117">このポイント以降のすべての進行状況を完了することはできません。</span><span class="sxs-lookup"><span data-stu-id="4508d-117">All progress past this point should be undone.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="4508d-118"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4508d-118">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="4508d-119">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="4508d-119">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="4508d-120">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="4508d-120">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4508d-121">経由で提供されている特定のコミット シーケンス番号を超えるその進行状況を示す<see cref="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupCommitAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" />完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4508d-121">Indicates that progress beyond a particular commit sequence number that is provided via <see cref="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupCommitAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" /> should be undone.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="4508d-122"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="4508d-122">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>