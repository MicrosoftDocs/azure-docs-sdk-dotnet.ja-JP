<Type Name="ComputeNodeGetBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeGetBatchRequest">
  <TypeSignature Language="C#" Value="public class ComputeNodeGetBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeGetBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeGetBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeGetBatchRequest&#xA;Inherits BatchRequest(Of ComputeNodeGetOptions, AzureOperationResponse(Of ComputeNode, ComputeNodeGetHeaders))" />
  <TypeSignature Language="F#" Value="type ComputeNodeGetBatchRequest = class&#xA;    inherit BatchRequest&lt;ComputeNodeGetOptions, AzureOperationResponse&lt;ComputeNode, ComputeNodeGetHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> ComputeNodeGet 操作します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeGetBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeGetBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeGetBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeGetBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeGetBatchRequest (serviceClient, cancellationToken)" />
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
        <param name="serviceClient">サービスを使用するクライアント。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.ComputeNodeGetBatchRequest" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>