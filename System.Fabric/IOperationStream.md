<Type Name="IOperationStream" FullName="System.Fabric.IOperationStream">
  <TypeSignature Language="C#" Value="public interface IOperationStream" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperationStream" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IOperationStream" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperationStream" />
  <TypeSignature Language="F#" Value="type IOperationStream = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>レプリケーションまたはプライマリからセカンダリ レプリカに送信されるコピー操作のストリームを表します。  </para>
    </summary>
    <remarks>
      <para>返されたストリーム<see cref="M:System.Fabric.IStateReplicator.GetCopyStream" />と<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />を実装するオブジェクトは、<see cref="T:System.Fabric.IOperationStream" />です。</para>
    </remarks>
    <exception cref="T:System.TimeoutException">
      <para>プロセスまたは操作用に割り当てられた時間が経過したときにスローされる例外。</para>
    </exception>
  </Docs>
  <Members>
    <Member MemberName="GetOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IOperation&gt; GetOperationAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IOperation&gt; GetOperationAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOperationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IOperation&gt;" Usage="iOperationStream.GetOperationAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>実装する次のオブジェクトを取得<see cref="T:System.Fabric.IOperation" />、基になるから<see cref="T:System.Fabric.IOperationStream" />です。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.Fabric.IOperation" />します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>