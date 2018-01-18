<Type Name="FileListFromComputeNodeBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.FileListFromComputeNodeBatchRequest">
  <TypeSignature Language="C#" Value="public class FileListFromComputeNodeBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Nullable&lt;bool&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileListFromComputeNodeBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;valuetype System.Nullable`1&lt;bool&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileListFromComputeNodeBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class FileListFromComputeNodeBatchRequest&#xA;Inherits BatchRequest(Of Nullable(Of Boolean), FileListFromComputeNodeOptions, AzureOperationResponse(Of IPage(Of NodeFile), FileListFromComputeNodeHeaders))" />
  <TypeSignature Language="F#" Value="type FileListFromComputeNodeBatchRequest = class&#xA;    inherit BatchRequest&lt;Nullable&lt;bool&gt;, FileListFromComputeNodeOptions, AzureOperationResponse&lt;IPage&lt;NodeFile&gt;, FileListFromComputeNodeHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;System.Nullable&lt;System.Boolean&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">System.Nullable&lt;System.Boolean&gt;</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeFile&gt;,Microsoft.Azure.Batch.Protocol.Models.FileListFromComputeNodeHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="97f3d-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> FileListFromComputeNode 操作します。</span><span class="sxs-lookup"><span data-stu-id="97f3d-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the FileListFromComputeNode operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileListFromComputeNodeBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Nullable&lt;bool&gt; parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Nullable`1&lt;bool&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.FileListFromComputeNodeBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileListFromComputeNodeBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.FileListFromComputeNodeBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileListFromComputeNodeBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="97f3d-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="97f3d-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="97f3d-103">使用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="97f3d-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="97f3d-104">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="97f3d-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="97f3d-105"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileListFromComputeNodeBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="97f3d-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileListFromComputeNodeBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>