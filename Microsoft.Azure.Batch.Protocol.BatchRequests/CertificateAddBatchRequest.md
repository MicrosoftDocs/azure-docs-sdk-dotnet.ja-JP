<Type Name="CertificateAddBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateAddBatchRequest">
  <TypeSignature Language="C#" Value="public class CertificateAddBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateAddBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateAddBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateAddBatchRequest&#xA;Inherits BatchRequest(Of CertificateAddParameter, CertificateAddOptions, AzureOperationHeaderResponse(Of CertificateAddHeaders))" />
  <TypeSignature Language="F#" Value="type CertificateAddBatchRequest = class&#xA;    inherit BatchRequest&lt;CertificateAddParameter, CertificateAddOptions, AzureOperationHeaderResponse&lt;CertificateAddHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fdab7-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />を参照してください操作します。</span><span class="sxs-lookup"><span data-stu-id="fdab7-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the CertificateAdd operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateAddBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateAddBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateAddBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateAddBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateAddBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="fdab7-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="fdab7-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="fdab7-103">使用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="fdab7-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fdab7-104">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="fdab7-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="fdab7-105"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateAddBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdab7-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.CertificateAddBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>