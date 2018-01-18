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
      <para><span data-ttu-id="dfd3a-101">レプリケーションまたはプライマリからセカンダリ レプリカに送信されるコピー操作のストリームを表します。</span><span class="sxs-lookup"><span data-stu-id="dfd3a-101">Represents a stream of replication or copy operations that are sent from the Primary to the Secondary replica.</span></span>  </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="dfd3a-102">返されたストリーム<see cref="M:System.Fabric.IStateReplicator.GetCopyStream" />と<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />を実装するオブジェクトは、<see cref="T:System.Fabric.IOperationStream" />です。</span><span class="sxs-lookup"><span data-stu-id="dfd3a-102">The streams returned from <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> and <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> are objects that implement <see cref="T:System.Fabric.IOperationStream" />.</span></span></para>
    </remarks>
    <exception cref="T:System.TimeoutException">
      <para><span data-ttu-id="dfd3a-103">プロセスまたは操作用に割り当てられた時間が経過したときにスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="dfd3a-103">The exception that is thrown when the time allotted for a process or operation has expired.</span></span></para>
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
          <para><span data-ttu-id="dfd3a-104"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="dfd3a-104">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="dfd3a-105">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="dfd3a-105">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="dfd3a-106">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="dfd3a-106">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="dfd3a-107">実装する次のオブジェクトを取得<see cref="T:System.Fabric.IOperation" />、基になるから<see cref="T:System.Fabric.IOperationStream" />です。</span><span class="sxs-lookup"><span data-stu-id="dfd3a-107">Gets the next object that implements <see cref="T:System.Fabric.IOperation" /> from the underlying <see cref="T:System.Fabric.IOperationStream" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="dfd3a-108">返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.Fabric.IOperation" />します。</span><span class="sxs-lookup"><span data-stu-id="dfd3a-108">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.Fabric.IOperation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>