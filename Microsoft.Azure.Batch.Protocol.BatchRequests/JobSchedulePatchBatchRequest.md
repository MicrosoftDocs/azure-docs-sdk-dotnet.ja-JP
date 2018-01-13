<Type Name="JobSchedulePatchBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.JobSchedulePatchBatchRequest">
  <TypeSignature Language="C#" Value="public class JobSchedulePatchBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobSchedulePatchBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.JobSchedulePatchBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class JobSchedulePatchBatchRequest&#xA;Inherits BatchRequest(Of JobSchedulePatchParameter, JobSchedulePatchOptions, AzureOperationHeaderResponse(Of JobSchedulePatchHeaders))" />
  <TypeSignature Language="F#" Value="type JobSchedulePatchBatchRequest = class&#xA;    inherit BatchRequest&lt;JobSchedulePatchParameter, JobSchedulePatchOptions, AzureOperationHeaderResponse&lt;JobSchedulePatchHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="969c8-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> JobSchedulePatch 操作します。</span><span class="sxs-lookup"><span data-stu-id="969c8-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the JobSchedulePatch operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSchedulePatchBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.JobSchedulePatchBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.JobSchedulePatchBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.JobSchedulePatchBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.JobSchedulePatchBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="969c8-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="969c8-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="969c8-103">使用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="969c8-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="969c8-104">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="969c8-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="969c8-105"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.JobSchedulePatchBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="969c8-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.JobSchedulePatchBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>