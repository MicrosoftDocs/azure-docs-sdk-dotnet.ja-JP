<Type Name="ErrorCategory" FullName="Microsoft.Azure.Batch.Common.ErrorCategory">
  <TypeSignature Language="C#" Value="public enum ErrorCategory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ErrorCategory extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ErrorCategory" />
  <TypeSignature Language="VB.NET" Value="Public Enum ErrorCategory" />
  <TypeSignature Language="F#" Value="type ErrorCategory = " />
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
            <span data-ttu-id="e2c3b-101">タスクのスケジュール エラーのカテゴリ。</span><span class="sxs-lookup"><span data-stu-id="e2c3b-101">The category of a task scheduling error.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ServerError">
      <MemberSignature Language="C#" Value="ServerError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ErrorCategory ServerError = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ErrorCategory.ServerError" />
      <MemberSignature Language="VB.NET" Value="ServerError" />
      <MemberSignature Language="F#" Value="ServerError = 1" Usage="Microsoft.Azure.Batch.Common.ErrorCategory.ServerError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ErrorCategory</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2c3b-102">バッチ サービスでエラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="e2c3b-102">The error occurred in the Batch service.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="UserError">
      <MemberSignature Language="C#" Value="UserError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ErrorCategory UserError = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ErrorCategory.UserError" />
      <MemberSignature Language="VB.NET" Value="UserError" />
      <MemberSignature Language="F#" Value="UserError = 0" Usage="Microsoft.Azure.Batch.Common.ErrorCategory.UserError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ErrorCategory</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2c3b-103">エラーは、ユーザーによって提供されるタスクの仕様でした。</span><span class="sxs-lookup"><span data-stu-id="e2c3b-103">The error was in the task specification provided by the user.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>