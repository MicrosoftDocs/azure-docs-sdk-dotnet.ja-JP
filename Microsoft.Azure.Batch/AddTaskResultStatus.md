<Type Name="AddTaskResultStatus" FullName="Microsoft.Azure.Batch.AddTaskResultStatus">
  <TypeSignature Language="C#" Value="public enum AddTaskResultStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed AddTaskResultStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AddTaskResultStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum AddTaskResultStatus" />
  <TypeSignature Language="F#" Value="type AddTaskResultStatus = " />
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
            <span data-ttu-id="7afa7-101">によって使用される<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />を分類する、<see cref="T:Microsoft.Azure.Batch.AddTaskResult" />に成功したかが必要である、再試行します。</span><span class="sxs-lookup"><span data-stu-id="7afa7-101">Used by <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> to classify an <see cref="T:Microsoft.Azure.Batch.AddTaskResult" /> as successful or requiring a retry.</span></span>
            </summary>
    <remarks><span data-ttu-id="7afa7-102">エラーを報告する再試行不可能な; AddTaskResultStatus は使用されません。結果のハンドラーをスローする必要があります<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionTerminatedException" />用です。</span><span class="sxs-lookup"><span data-stu-id="7afa7-102">AddTaskResultStatus is not used to report non-retryable failure; a result handler should throw <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionTerminatedException" /> for that.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="Retry">
      <MemberSignature Language="C#" Value="Retry" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.AddTaskResultStatus Retry = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.AddTaskResultStatus.Retry" />
      <MemberSignature Language="VB.NET" Value="Retry" />
      <MemberSignature Language="F#" Value="Retry = 1" Usage="Microsoft.Azure.Batch.AddTaskResultStatus.Retry" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AddTaskResultStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="7afa7-103">再試行を必要とすると結果を分類します。</span><span class="sxs-lookup"><span data-stu-id="7afa7-103">Classifies the result as requiring a retry.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="Success" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.AddTaskResultStatus Success = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.AddTaskResultStatus.Success" />
      <MemberSignature Language="VB.NET" Value="Success" />
      <MemberSignature Language="F#" Value="Success = 0" Usage="Microsoft.Azure.Batch.AddTaskResultStatus.Success" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AddTaskResultStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="7afa7-104">結果を成功として分類します。</span><span class="sxs-lookup"><span data-stu-id="7afa7-104">Classifies the result as a success.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>