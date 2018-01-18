<Type Name="TaskListBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListBatchRequest">
  <TypeSignature Language="C#" Value="public class TaskListBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.TaskListOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskListBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, class Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskListBatchRequest&#xA;Inherits BatchRequest(Of TaskListOptions, AzureOperationResponse(Of IPage(Of CloudTask), TaskListHeaders))" />
  <TypeSignature Language="F#" Value="type TaskListBatchRequest = class&#xA;    inherit BatchRequest&lt;TaskListOptions, AzureOperationResponse&lt;IPage&lt;CloudTask&gt;, TaskListHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.TaskListOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.TaskListOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="443bc-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> TaskList 操作します。</span><span class="sxs-lookup"><span data-stu-id="443bc-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the TaskList operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskListBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListBatchRequest (serviceClient, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="443bc-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="443bc-102">The service client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="443bc-103">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="443bc-103">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="443bc-104"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="443bc-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>