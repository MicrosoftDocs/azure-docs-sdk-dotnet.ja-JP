<Type Name="PoolAddBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.PoolAddBatchRequest">
  <TypeSignature Language="C#" Value="public class PoolAddBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter,Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolAddBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolAddBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolAddBatchRequest&#xA;Inherits BatchRequest(Of PoolAddParameter, PoolAddOptions, AzureOperationHeaderResponse(Of PoolAddHeaders))" />
  <TypeSignature Language="F#" Value="type PoolAddBatchRequest = class&#xA;    inherit BatchRequest&lt;PoolAddParameter, PoolAddOptions, AzureOperationHeaderResponse&lt;PoolAddHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter,Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d8c42-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />元操作します。</span><span class="sxs-lookup"><span data-stu-id="d8c42-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the PoolAdd operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolAddBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, class Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolAddBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolAddBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.PoolAddBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolAddBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="d8c42-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="d8c42-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="d8c42-103">使用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="d8c42-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d8c42-104">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="d8c42-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="d8c42-105"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolAddBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d8c42-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolAddBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>