<Type Name="AccessScope" FullName="Microsoft.Azure.Batch.Common.AccessScope">
  <TypeSignature Language="C#" Value="public enum AccessScope" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed AccessScope extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.AccessScope" />
  <TypeSignature Language="VB.NET" Value="Public Enum AccessScope" />
  <TypeSignature Language="F#" Value="type AccessScope = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="32f98-101">を介して提供される認証トークンを使用して、タスクがアクセスできる Batch リソース、<see cref="P:Microsoft.Azure.Batch.CloudTask.AuthenticationTokenSettings" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="32f98-101">The Batch resources that can be accessed by a task using an authentication token provided via the <see cref="P:Microsoft.Azure.Batch.CloudTask.AuthenticationTokenSettings" /> property.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Job">
      <MemberSignature Language="C#" Value="Job" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.AccessScope Job = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.AccessScope.Job" />
      <MemberSignature Language="VB.NET" Value="Job" />
      <MemberSignature Language="F#" Value="Job = 1" Usage="Microsoft.Azure.Batch.Common.AccessScope.Job" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AccessScope</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="32f98-102">認証トークンは、タスクが含まれているジョブへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="32f98-102">The authentication token permits access to the job that contains the task.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.AccessScope None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.AccessScope.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.Azure.Batch.Common.AccessScope.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AccessScope</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="32f98-103">認証トークンは、すべてのリソースへのアクセスを付与しません。</span><span class="sxs-lookup"><span data-stu-id="32f98-103">The authentication token does not grant access to any resources.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>