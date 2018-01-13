<Type Name="PoolPatchBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.PoolPatchBatchRequest">
  <TypeSignature Language="C#" Value="public class PoolPatchBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter,Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolPatchBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolPatchBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolPatchBatchRequest&#xA;Inherits BatchRequest(Of PoolPatchParameter, PoolPatchOptions, AzureOperationHeaderResponse(Of PoolPatchHeaders))" />
  <TypeSignature Language="F#" Value="type PoolPatchBatchRequest = class&#xA;    inherit BatchRequest&lt;PoolPatchParameter, PoolPatchOptions, AzureOperationHeaderResponse&lt;PoolPatchHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter,Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> PoolPatch 操作します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolPatchBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolPatchBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolPatchBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.PoolPatchBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.PoolPatchBatchRequest (serviceClient, parameters, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient">サービスを使用するクライアント。</param>
        <param name="parameters">使用するパラメーター。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.PoolPatchBatchRequest" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>