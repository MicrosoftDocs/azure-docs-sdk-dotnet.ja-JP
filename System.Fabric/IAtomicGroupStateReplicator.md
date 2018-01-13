<Type Name="IAtomicGroupStateReplicator" FullName="System.Fabric.IAtomicGroupStateReplicator">
  <TypeSignature Language="C#" Value="public interface IAtomicGroupStateReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAtomicGroupStateReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IAtomicGroupStateReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAtomicGroupStateReplicator" />
  <TypeSignature Language="F#" Value="type IAtomicGroupStateReplicator = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>分割不可能なグループのレプリケーション関連の機能を公開します。 </para>
    </summary>
    <remarks>
      <para><see cref="T:System.Fabric.IAtomicGroupStateReplicator" />利用できるサービスがサービス グループのメンバーである場合です。 サービスを実装する必要があります<see cref="T:System.Fabric.IAtomicGroupStateProvider" />ステートフルであるとします。 作成するときに、<see cref="T:System.Fabric.FabricReplicator" />経由で<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />、通常で渡す代わりに<see cref="T:System.Fabric.IStateProvider" />、サービスで渡すことができます、<see cref="T:System.Fabric.IAtomicGroupStateProvider" />代わりに実装します。 その結果、受信、<see cref="T:System.Fabric.IAtomicGroupStateReplicator" />です。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAtomicGroup">
      <MemberSignature Language="C#" Value="public long CreateAtomicGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 CreateAtomicGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.CreateAtomicGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAtomicGroup () As Long" />
      <MemberSignature Language="F#" Value="abstract member CreateAtomicGroup : unit -&gt; int64" Usage="iAtomicGroupStateReplicator.CreateAtomicGroup " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>新しい分割不可能なグループを作成し、分割不可能なグループの ID を取得します。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Int64" />作成したアトミック グループの ID。</para>
        </returns>
        <remarks>
          <para>分割不可能なグループは、サービス グループのメンバー間で一連の変更を調整するために使用されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupCommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupCommitAsync (long atomicGroupId, System.Threading.CancellationToken cancellationToken, out long commitSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupCommitAsync(int64 atomicGroupId, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; commitSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupCommitAsync(System.Int64,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupCommitAsync : int64 * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupCommitAsync (atomicGroupId, cancellationToken, commitSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="commitSequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para>コミットするグループの ID。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <param name="commitSequenceNumber">
          <para>Out パラメーターとして、コミット操作の LSN です。</para>
        </param>
        <summary>
          <para>アトミック グループの状態のレプリケーションを非同期にコミットします。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" />型の長い、コミット操作の LSN。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupOperationAsync (long atomicGroupId, System.Fabric.OperationData operationData, System.Threading.CancellationToken cancellationToken, out long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupOperationAsync(int64 atomicGroupId, class System.Fabric.OperationData operationData, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupOperationAsync(System.Int64,System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupOperationAsync : int64 * System.Fabric.OperationData * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupOperationAsync (atomicGroupId, operationData, cancellationToken, sequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="operationData" Type="System.Fabric.OperationData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="sequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para>取得されるアトミック グループの ID<see cref="M:System.Fabric.IAtomicGroupStateReplicator.CreateAtomicGroup" />が含まれています、<see cref="T:System.Fabric.OperationData" />です。</para>
        </param>
        <param name="operationData">
          <para><see cref="T:System.Fabric.OperationData" />をレプリケートします。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を観察し CancellationToken オブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <param name="sequenceNumber">
          <para>Out パラメーターとして、操作の LSN。</para>
        </param>
        <summary>
          <para>一部の複製<see cref="T:System.Fabric.OperationData" />アトミック グループの一部として。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" />long 型で、レプリケートされたアトミック グループ操作の LSN。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupRollbackAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupRollbackAsync (long atomicGroupId, System.Threading.CancellationToken cancellationToken, out long rollbackSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupRollbackAsync(int64 atomicGroupId, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; rollbackSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupRollbackAsync(System.Int64,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupRollbackAsync : int64 * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupRollbackAsync (atomicGroupId, cancellationToken, rollbackSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="rollbackSequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para>ロールバックするアトミック グループの ID。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <param name="rollbackSequenceNumber">
          <para>Out パラメーターとして、ロールバック操作の LSN。</para>
        </param>
        <summary>
          <para>非同期的にロールバック アトミック グループの状態のレプリケーション。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" />long 型でロールバック操作の LSN。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>