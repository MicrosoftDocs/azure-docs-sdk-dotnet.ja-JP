<Type Name="ComputeNodeRebootBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeRebootBatchRequest">
  <TypeSignature Language="C#" Value="public class ComputeNodeRebootBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeRebootBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeRebootBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeRebootBatchRequest&#xA;Inherits BatchRequest(Of Nullable(Of ComputeNodeRebootOption), ComputeNodeRebootOptions, AzureOperationHeaderResponse(Of ComputeNodeRebootHeaders))" />
  <TypeSignature Language="F#" Value="type ComputeNodeRebootBatchRequest = class&#xA;    inherit BatchRequest&lt;Nullable&lt;ComputeNodeRebootOption&gt;, ComputeNodeRebootOptions, AzureOperationHeaderResponse&lt;ComputeNodeRebootHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c5b9a-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> ComputeNodeReboot 操作します。</span><span class="sxs-lookup"><span data-stu-id="c5b9a-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the ComputeNodeReboot operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeRebootBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeRebootBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeRebootBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeRebootBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeRebootBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="c5b9a-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="c5b9a-102">The service client to use.</span></span></param>
        <param name="parameters"><span data-ttu-id="c5b9a-103">使用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c5b9a-103">The parameters to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c5b9a-104">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="c5b9a-104">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="c5b9a-105"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeRebootBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c5b9a-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeRebootBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>