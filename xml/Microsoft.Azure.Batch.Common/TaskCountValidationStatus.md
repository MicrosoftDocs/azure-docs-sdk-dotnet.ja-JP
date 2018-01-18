<Type Name="TaskCountValidationStatus" FullName="Microsoft.Azure.Batch.Common.TaskCountValidationStatus">
  <TypeSignature Language="C#" Value="public enum TaskCountValidationStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TaskCountValidationStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.TaskCountValidationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum TaskCountValidationStatus" />
  <TypeSignature Language="F#" Value="type TaskCountValidationStatus = " />
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
            <span data-ttu-id="53ebf-101">タスクをカウントするかどうかが検証されました。</span><span class="sxs-lookup"><span data-stu-id="53ebf-101">Whether the task counts have been validated.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Unvalidated">
      <MemberSignature Language="C#" Value="Unvalidated" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.TaskCountValidationStatus Unvalidated = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.TaskCountValidationStatus.Unvalidated" />
      <MemberSignature Language="VB.NET" Value="Unvalidated" />
      <MemberSignature Language="F#" Value="Unvalidated = 1" Usage="Microsoft.Azure.Batch.Common.TaskCountValidationStatus.Unvalidated" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskCountValidationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
             <span data-ttu-id="53ebf-102">バッチ サービスでは、一覧のタスクの API で報告されるタスクの状態に対して状態の数を確認することがされていません。</span><span class="sxs-lookup"><span data-stu-id="53ebf-102">The Batch service has not been able to check state counts against the task states as reported in the List Tasks API.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Validated">
      <MemberSignature Language="C#" Value="Validated" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.TaskCountValidationStatus Validated = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.TaskCountValidationStatus.Validated" />
      <MemberSignature Language="VB.NET" Value="Validated" />
      <MemberSignature Language="F#" Value="Validated = 0" Usage="Microsoft.Azure.Batch.Common.TaskCountValidationStatus.Validated" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskCountValidationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="53ebf-103">タスク数は、検証されているし、タスク一覧の結果を照合することが保証されます。</span><span class="sxs-lookup"><span data-stu-id="53ebf-103">The task counts have been validated and are guaranteed to match the List Tasks results.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>