<Type Name="FileGetFromTaskBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromTaskBatchRequest">
  <TypeSignature Language="C#" Value="public class FileGetFromTaskBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileGetFromTaskBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class System.IO.Stream, class Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromTaskBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class FileGetFromTaskBatchRequest&#xA;Inherits BatchRequest(Of FileGetFromTaskOptions, AzureOperationResponse(Of Stream, FileGetFromTaskHeaders))" />
  <TypeSignature Language="F#" Value="type FileGetFromTaskBatchRequest = class&#xA;    inherit BatchRequest&lt;FileGetFromTaskOptions, AzureOperationResponse&lt;Stream, FileGetFromTaskHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cd950-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> FileGetFromTask 操作します。</span><span class="sxs-lookup"><span data-stu-id="cd950-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the FileGetFromTask operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetFromTaskBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromTaskBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromTaskBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromTaskBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromTaskBatchRequest (serviceClient, cancellationToken)" />
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
        <param name="serviceClient"><span data-ttu-id="cd950-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="cd950-102">The service client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="cd950-103">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="cd950-103">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="cd950-104"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromTaskBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cd950-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileGetFromTaskBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>