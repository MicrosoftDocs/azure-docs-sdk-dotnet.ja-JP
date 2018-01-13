<Type Name="ComputeNodeListBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeListBatchRequest">
  <TypeSignature Language="C#" Value="public class ComputeNodeListBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeListBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeListBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeListBatchRequest&#xA;Inherits BatchRequest(Of ComputeNodeListOptions, AzureOperationResponse(Of IPage(Of ComputeNode), ComputeNodeListHeaders))" />
  <TypeSignature Language="F#" Value="type ComputeNodeListBatchRequest = class&#xA;    inherit BatchRequest&lt;ComputeNodeListOptions, AzureOperationResponse&lt;IPage&lt;ComputeNode&gt;, ComputeNodeListHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9a432-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> ComputeNodeList 操作します。</span><span class="sxs-lookup"><span data-stu-id="9a432-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the ComputeNodeList operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeListBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeListBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeListBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeListBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeListBatchRequest (serviceClient, cancellationToken)" />
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
        <param name="serviceClient"><span data-ttu-id="9a432-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="9a432-102">The service client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="9a432-103">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="9a432-103">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="9a432-104"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeListBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9a432-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeListBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>