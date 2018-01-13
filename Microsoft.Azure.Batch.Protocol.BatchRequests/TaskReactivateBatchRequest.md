<Type Name="TaskReactivateBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.TaskReactivateBatchRequest">
  <TypeSignature Language="C#" Value="public class TaskReactivateBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskReactivateBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions, class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskReactivateBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskReactivateBatchRequest&#xA;Inherits BatchRequest(Of TaskReactivateOptions, AzureOperationHeaderResponse(Of TaskReactivateHeaders))" />
  <TypeSignature Language="F#" Value="type TaskReactivateBatchRequest = class&#xA;    inherit BatchRequest&lt;TaskReactivateOptions, AzureOperationHeaderResponse&lt;TaskReactivateHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions,Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> TaskReactivate 操作します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskReactivateBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskReactivateBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.TaskReactivateBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.TaskReactivateBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.TaskReactivateBatchRequest (serviceClient, cancellationToken)" />
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
            <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskReactivateBatchRequest" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>