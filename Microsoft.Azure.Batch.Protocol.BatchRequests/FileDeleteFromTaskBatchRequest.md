<Type Name="FileDeleteFromTaskBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromTaskBatchRequest">
  <TypeSignature Language="C#" Value="public class FileDeleteFromTaskBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Nullable&lt;bool&gt;,Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileDeleteFromTaskBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`3&lt;valuetype System.Nullable`1&lt;bool&gt;, class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromTaskBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class FileDeleteFromTaskBatchRequest&#xA;Inherits BatchRequest(Of Nullable(Of Boolean), FileDeleteFromTaskOptions, AzureOperationHeaderResponse(Of FileDeleteFromTaskHeaders))" />
  <TypeSignature Language="F#" Value="type FileDeleteFromTaskBatchRequest = class&#xA;    inherit BatchRequest&lt;Nullable&lt;bool&gt;, FileDeleteFromTaskOptions, AzureOperationHeaderResponse&lt;FileDeleteFromTaskHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;System.Nullable&lt;System.Boolean&gt;,Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TBody">System.Nullable&lt;System.Boolean&gt;</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.FileDeleteFromTaskHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> FileDeleteFromTask 操作します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileDeleteFromTaskBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, Nullable&lt;bool&gt; parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Nullable`1&lt;bool&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromTaskBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromTaskBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromTaskBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromTaskBatchRequest (serviceClient, parameters, cancellationToken)" />
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
        <param name="serviceClient">サービスを使用するクライアント。</param>
        <param name="parameters">使用するパラメーター。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.FileDeleteFromTaskBatchRequest" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>