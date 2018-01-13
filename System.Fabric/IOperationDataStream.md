<Type Name="IOperationDataStream" FullName="System.Fabric.IOperationDataStream">
  <TypeSignature Language="C#" Value="public interface IOperationDataStream" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperationDataStream" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IOperationDataStream" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperationDataStream" />
  <TypeSignature Language="F#" Value="type IOperationDataStream = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para> <span data-ttu-id="5878d-101"><see cref="T:System.Fabric.IOperationDataStream" />のストリームをカプセル化<see cref="T:System.Fabric.OperationData" />プライマリ レプリカとセカンダリ レプリカ間で交換されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5878d-101">An <see cref="T:System.Fabric.IOperationDataStream" /> encapsulates a stream of <see cref="T:System.Fabric.OperationData" /> objects that are exchanged between Primary replica and Secondary replica.</span></span>
            <span data-ttu-id="5878d-102">実装するオブジェクト<see cref="T:System.Fabric.IOperationDataStream" />コピー処理中に使用します。</span><span class="sxs-lookup"><span data-stu-id="5878d-102">Objects that implement <see cref="T:System.Fabric.IOperationDataStream" /> are used during the copy process.</span></span>
            <span data-ttu-id="5878d-103">コピー コンテキスト<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />メソッドは、プライマリ レプリカとコピー状態をセカンダリ レプリカから送信される<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />メソッドの実装、<see cref="T:System.Fabric.IOperationDataStream" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="5878d-103">Both the copy context <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> method that is sent from the Secondary replica to the Primary replica and the copy state <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> method implement the <see cref="T:System.Fabric.IOperationDataStream" /> interface.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.OperationData&gt; GetNextAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.OperationData&gt; GetNextAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IOperationDataStream.GetNextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetNextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.OperationData&gt;" Usage="iOperationDataStream.GetNextAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.MSInternal", "CA908:UseApprovedGenericsForPrecompiledAssemblies", Justification="Not precompiled assembly.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.OperationData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="5878d-104">非同期操作をキャンセルするためのメカニズムを提供します。</span><span class="sxs-lookup"><span data-stu-id="5878d-104">Provides a mechanism to cancel the asynchronous operation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5878d-105">次の取得<see cref="T:System.Fabric.OperationData" />オブジェクトから、<see cref="T:System.Fabric.IOperationDataStream" />です。</span><span class="sxs-lookup"><span data-stu-id="5878d-105">Gets the next <see cref="T:System.Fabric.OperationData" /> object from the <see cref="T:System.Fabric.IOperationDataStream" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5878d-106">返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.Fabric.OperationData" />します。</span><span class="sxs-lookup"><span data-stu-id="5878d-106">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.Fabric.OperationData" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="5878d-107">Null を返すことを示す、システムに転送が完了しました。</span><span class="sxs-lookup"><span data-stu-id="5878d-107">Returning null indicates to the system that the transfer is complete.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>