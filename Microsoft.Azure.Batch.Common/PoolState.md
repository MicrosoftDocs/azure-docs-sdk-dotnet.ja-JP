<Type Name="PoolState" FullName="Microsoft.Azure.Batch.Common.PoolState">
  <TypeSignature Language="C#" Value="public enum PoolState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PoolState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.PoolState" />
  <TypeSignature Language="VB.NET" Value="Public Enum PoolState" />
  <TypeSignature Language="F#" Value="type PoolState = " />
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
            <span data-ttu-id="fe789-101">プールの状態。</span><span class="sxs-lookup"><span data-stu-id="fe789-101">The state of a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.PoolState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Common.PoolState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.PoolState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe789-102">プールは、コンピューティング ノードの可用性の対象のタスクを実行できるようにします。</span><span class="sxs-lookup"><span data-stu-id="fe789-102">The pool is available to run tasks subject to the availability of compute nodes.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.PoolState Deleting = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 1" Usage="Microsoft.Azure.Batch.Common.PoolState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.PoolState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe789-103">ユーザーが、プールが削除されることを要求しましたが、削除操作がまだ完了していません。</span><span class="sxs-lookup"><span data-stu-id="fe789-103">The user has requested that the pool be deleted, but the delete operation has not yet completed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Upgrading">
      <MemberSignature Language="C#" Value="Upgrading" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.PoolState Upgrading = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />
      <MemberSignature Language="VB.NET" Value="Upgrading" />
      <MemberSignature Language="F#" Value="Upgrading = 2" Usage="Microsoft.Azure.Batch.Common.PoolState.Upgrading" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.PoolState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe789-104">ユーザーが、プールのノードのオペレーティング システムをアップグレードすることを要求しましたが、アップグレード操作がまだ完了していない (つまり、プール内のいくつかのノードがまだアップグレードされていない)。</span><span class="sxs-lookup"><span data-stu-id="fe789-104">The user has requested that the operating system of the pool's nodes be upgraded, but the upgrade operation has not yet completed (that is, some nodes in the pool have not yet been upgraded).</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>