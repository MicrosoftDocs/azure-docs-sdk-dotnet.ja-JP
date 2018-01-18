<Type Name="TaskUpdateBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.TaskUpdateBatchRequest">
  <TypeSignature Language="C#" Value="public class TaskUpdateBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskUpdateBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskUpdateBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskUpdateBatchRequest&#xA;Inherits BatchRequest(Of TaskConstraints, TaskUpdateOptions, AzureOperationHeaderResponse(Of TaskUpdateHeaders))" />
  <TypeSignature Language="F#" Value="type TaskUpdateBatchRequest = class&#xA;    inherit BatchRequest&lt;TaskConstraints, TaskUpdateOptions, AzureOperationHeaderResponse&lt;TaskUpdateHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">Microsoft.Azure.Batch.Protocol.Models.TaskConstraints</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e4d64-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> TaskUpdate 操作します。</span><span class="sxs-lookup"><span data-stu-id="e4d64-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the TaskUpdate operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskUpdateBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskUpdateBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.TaskUpdateBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.TaskUpdateBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.TaskUpdateBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="e4d64-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="e4d64-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="e4d64-103">使用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="e4d64-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="e4d64-104">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="e4d64-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="e4d64-105"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskUpdateBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e4d64-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskUpdateBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>