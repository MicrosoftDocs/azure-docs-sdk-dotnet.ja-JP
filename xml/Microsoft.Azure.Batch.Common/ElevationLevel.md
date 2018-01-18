<Type Name="ElevationLevel" FullName="Microsoft.Azure.Batch.Common.ElevationLevel">
  <TypeSignature Language="C#" Value="public enum ElevationLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ElevationLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ElevationLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum ElevationLevel" />
  <TypeSignature Language="F#" Value="type ElevationLevel = " />
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
            <span data-ttu-id="67671-101">タスクの実行に、Batch service によって使用されるユーザー アカウントの昇格レベル。</span><span class="sxs-lookup"><span data-stu-id="67671-101">The elevation level of the user account used by the Batch service to execute a task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Admin">
      <MemberSignature Language="C#" Value="Admin" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ElevationLevel Admin = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ElevationLevel.Admin" />
      <MemberSignature Language="VB.NET" Value="Admin" />
      <MemberSignature Language="F#" Value="Admin = 1" Usage="Microsoft.Azure.Batch.Common.ElevationLevel.Admin" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ElevationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="67671-102">ユーザーは、アクセスが高度なされ、完全な管理者アクセス許可で操作を行います。</span><span class="sxs-lookup"><span data-stu-id="67671-102">The user has elevated access and operates with full Administrator permissions.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NonAdmin">
      <MemberSignature Language="C#" Value="NonAdmin" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ElevationLevel NonAdmin = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ElevationLevel.NonAdmin" />
      <MemberSignature Language="VB.NET" Value="NonAdmin" />
      <MemberSignature Language="F#" Value="NonAdmin = 0" Usage="Microsoft.Azure.Batch.Common.ElevationLevel.NonAdmin" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ElevationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="67671-103">ユーザーは、標準的なアクセス許可を持ちます。</span><span class="sxs-lookup"><span data-stu-id="67671-103">The user has standard access permissions.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>