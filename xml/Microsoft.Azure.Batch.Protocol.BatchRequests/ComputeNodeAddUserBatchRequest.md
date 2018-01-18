<Type Name="ComputeNodeAddUserBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeAddUserBatchRequest">
  <TypeSignature Language="C#" Value="public class ComputeNodeAddUserBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeAddUserBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeAddUserBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeAddUserBatchRequest&#xA;Inherits BatchRequest(Of ComputeNodeUser, ComputeNodeAddUserOptions, AzureOperationHeaderResponse(Of ComputeNodeAddUserHeaders))" />
  <TypeSignature Language="F#" Value="type ComputeNodeAddUserBatchRequest = class&#xA;    inherit BatchRequest&lt;ComputeNodeUser, ComputeNodeAddUserOptions, AzureOperationHeaderResponse&lt;ComputeNodeAddUserHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cf01b-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> ComputeNodeAddUser 操作します。</span><span class="sxs-lookup"><span data-stu-id="cf01b-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the ComputeNodeAddUser operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeAddUserBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeAddUserBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeAddUserBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeAddUserBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeAddUserBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="cf01b-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="cf01b-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="cf01b-103">使用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cf01b-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="cf01b-104">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="cf01b-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="cf01b-105"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeAddUserBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cf01b-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeAddUserBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>