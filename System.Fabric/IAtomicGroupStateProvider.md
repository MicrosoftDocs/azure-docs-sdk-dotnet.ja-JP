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
      <para>その他の方法について説明します、<see cref="T:System.Fabric.IAtomicGroupStateProvider" />インターフェイス ユーザー サービスがサービス グループのアトミック グループ機能を活用するために実装する必要があります。 </para>
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
          <para>コミットするグループの ID。</para>
        </param>
        <param name="commitSequenceNumber">
          <para>コミット操作のシーケンス番号。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>特定のアトミックなグループをコミットします。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Threading.Tasks.Task" /> を返します。</para>
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
          <para>ロールバックするグループの ID。</para>
        </param>
        <param name="rollbackSequenceNumber">
          <para>ロールバック操作のシーケンス番号。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>特定のアトミックなグループをロールバックします。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Threading.Tasks.Task" /> を返します。</para>
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
          <para>コミット操作の LSN。 このポイント以降のすべての進行状況を完了することはできません。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>経由で提供されている特定のコミット シーケンス番号を超えるその進行状況を示す<see cref="M:System.Fabric.IAtomicGroupStateProvider.AtomicGroupCommitAsync(System.Int64,System.Int64,System.Threading.CancellationToken)" />完了する必要があります。 </para>
        </summary>
        <returns>
          <para><see cref="T:System.Threading.Tasks.Task" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>