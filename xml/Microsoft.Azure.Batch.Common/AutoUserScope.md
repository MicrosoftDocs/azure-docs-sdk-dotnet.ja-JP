<Type Name="AutoUserScope" FullName="Microsoft.Azure.Batch.Common.AutoUserScope">
  <TypeSignature Language="C#" Value="public enum AutoUserScope" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed AutoUserScope extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.AutoUserScope" />
  <TypeSignature Language="VB.NET" Value="Public Enum AutoUserScope" />
  <TypeSignature Language="F#" Value="type AutoUserScope = " />
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
            <span data-ttu-id="21f50-101">タスクの実行に、Batch service によって使用されるユーザー アカウントのスコープです。</span><span class="sxs-lookup"><span data-stu-id="21f50-101">The scope of the user account used by the Batch service to execute a task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Pool">
      <MemberSignature Language="C#" Value="Pool" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.AutoUserScope Pool = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.AutoUserScope.Pool" />
      <MemberSignature Language="VB.NET" Value="Pool" />
      <MemberSignature Language="F#" Value="Pool = 1" Usage="Microsoft.Azure.Batch.Common.AutoUserScope.Pool" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AutoUserScope</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="21f50-102">タスクは、プール内の各ノードで作成される共通の自動ユーザー アカウントとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="21f50-102">The task runs as the common auto user account which is created on every node in a pool.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Task">
      <MemberSignature Language="C#" Value="Task" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.AutoUserScope Task = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.AutoUserScope.Task" />
      <MemberSignature Language="VB.NET" Value="Task" />
      <MemberSignature Language="F#" Value="Task = 0" Usage="Microsoft.Azure.Batch.Common.AutoUserScope.Task" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AutoUserScope</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="21f50-103">タスクは、タスクのために作成された新しいユーザーとして実行されます。</span><span class="sxs-lookup"><span data-stu-id="21f50-103">The task runs as a new user created specifically for the task.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>