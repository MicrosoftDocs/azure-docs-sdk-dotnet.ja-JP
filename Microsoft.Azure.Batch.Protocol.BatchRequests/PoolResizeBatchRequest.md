<Type Name="PoolResizeBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.PoolResizeBatchRequest">
  <TypeSignature Language="C#" Value="public class PoolResizeBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter,Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolResizeBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolResizeBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolResizeBatchRequest&#xA;Inherits BatchRequest(Of PoolResizeParameter, PoolResizeOptions, AzureOperationHeaderResponse(Of PoolResizeHeaders))" />
  <TypeSignature Language="F#" Value="type PoolResizeBatchRequest = class&#xA;    inherit BatchRequest&lt;PoolResizeParameter, PoolResizeOptions, AzureOperationHeaderResponse&lt;PoolResizeHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter,Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> PoolResize 操作します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolResizeBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolResizeBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolResizeBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.PoolResizeBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolResizeBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient">サービスを使用するクライアント。</param>
        <param name="parameters">使用するパラメーター。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolResizeBatchRequest" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>