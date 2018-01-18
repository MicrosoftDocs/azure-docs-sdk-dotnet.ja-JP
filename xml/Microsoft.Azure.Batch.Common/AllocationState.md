<Type Name="AllocationState" FullName="Microsoft.Azure.Batch.Common.AllocationState">
  <TypeSignature Language="C#" Value="public enum AllocationState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed AllocationState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.AllocationState" />
  <TypeSignature Language="VB.NET" Value="Public Enum AllocationState" />
  <TypeSignature Language="F#" Value="type AllocationState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="ec1fc-101">プールのサイズを変更するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="ec1fc-101">Indicates whether a pool is resizing.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Resizing">
      <MemberSignature Language="C#" Value="Resizing" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.AllocationState Resizing = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />
      <MemberSignature Language="VB.NET" Value="Resizing" />
      <MemberSignature Language="F#" Value="Resizing = 1" Usage="Microsoft.Azure.Batch.Common.AllocationState.Resizing" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AllocationState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec1fc-102">プールのサイズを変更します。つまり、コンピューティング ノードの中に追加またはプールから削除します。</span><span class="sxs-lookup"><span data-stu-id="ec1fc-102">The pool is resizing; that is, compute nodes are being added to or removed from the pool.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Steady">
      <MemberSignature Language="C#" Value="Steady" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.AllocationState Steady = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />
      <MemberSignature Language="VB.NET" Value="Steady" />
      <MemberSignature Language="F#" Value="Steady = 0" Usage="Microsoft.Azure.Batch.Common.AllocationState.Steady" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AllocationState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec1fc-103">プールのサイズを変更できません。</span><span class="sxs-lookup"><span data-stu-id="ec1fc-103">The pool is not resizing.</span></span> <span data-ttu-id="ec1fc-104">進行中のプール内のノードの数を変更することはありません。</span><span class="sxs-lookup"><span data-stu-id="ec1fc-104">There are no changes to the number of nodes in the pool in progress.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Stopping">
      <MemberSignature Language="C#" Value="Stopping" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.AllocationState Stopping = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" />
      <MemberSignature Language="VB.NET" Value="Stopping" />
      <MemberSignature Language="F#" Value="Stopping = 2" Usage="Microsoft.Azure.Batch.Common.AllocationState.Stopping" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AllocationState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec1fc-105">プールがサイズ変更が、ユーザーは、サイズ変更を停止することを要求したが、停止要求がまだ完了していません。</span><span class="sxs-lookup"><span data-stu-id="ec1fc-105">The pool was resizing, but the user has requested that the resize be stopped, but the stop request has not yet been completed.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>