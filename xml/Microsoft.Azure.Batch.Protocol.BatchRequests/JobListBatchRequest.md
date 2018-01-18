<Type Name="JobListBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.JobListBatchRequest">
  <TypeSignature Language="C#" Value="public class JobListBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.JobListOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobListBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.JobListOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.JobListBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class JobListBatchRequest&#xA;Inherits BatchRequest(Of JobListOptions, AzureOperationResponse(Of IPage(Of CloudJob), JobListHeaders))" />
  <TypeSignature Language="F#" Value="type JobListBatchRequest = class&#xA;    inherit BatchRequest&lt;JobListOptions, AzureOperationResponse&lt;IPage&lt;CloudJob&gt;, JobListHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.JobListOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.JobListOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3fe74-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> JobList 操作します。</span><span class="sxs-lookup"><span data-stu-id="3fe74-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the JobList operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobListBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.JobListBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.JobListBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.JobListBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.JobListBatchRequest (serviceClient, cancellationToken)" />
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
        <param name="serviceClient"><span data-ttu-id="3fe74-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="3fe74-102">The service client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="3fe74-103">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="3fe74-103">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="3fe74-104"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.JobListBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3fe74-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.JobListBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>