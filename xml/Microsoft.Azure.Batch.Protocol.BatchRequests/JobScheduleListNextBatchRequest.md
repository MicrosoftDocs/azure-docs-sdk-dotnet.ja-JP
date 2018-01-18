<Type Name="JobScheduleListNextBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.JobScheduleListNextBatchRequest">
  <TypeSignature Language="C#" Value="public class JobScheduleListNextBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleListNextBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.JobScheduleListNextBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleListNextBatchRequest&#xA;Inherits BatchRequest(Of JobScheduleListNextOptions, AzureOperationResponse(Of IPage(Of CloudJobSchedule), JobScheduleListHeaders))" />
  <TypeSignature Language="F#" Value="type JobScheduleListNextBatchRequest = class&#xA;    inherit BatchRequest&lt;JobScheduleListNextOptions, AzureOperationResponse&lt;IPage&lt;CloudJobSchedule&gt;, JobScheduleListHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="70ecb-101"><see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> JobScheduleListNext 操作します。</span><span class="sxs-lookup"><span data-stu-id="70ecb-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the JobScheduleListNext operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleListNextBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.JobScheduleListNextBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.JobScheduleListNextBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.JobScheduleListNextBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.JobScheduleListNextBatchRequest (serviceClient, cancellationToken)" />
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
        <param name="serviceClient"><span data-ttu-id="70ecb-102">サービスを使用するクライアント。</span><span class="sxs-lookup"><span data-stu-id="70ecb-102">The service client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="70ecb-103">A<see cref="T:System.Threading.CancellationToken" />要求の有効期間を制御します。</span><span class="sxs-lookup"><span data-stu-id="70ecb-103">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="70ecb-104"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.JobScheduleListNextBatchRequest" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="70ecb-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.JobScheduleListNextBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>