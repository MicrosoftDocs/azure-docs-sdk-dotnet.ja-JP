<Type Name="IBatchServiceClient" FullName="Microsoft.Azure.Batch.Protocol.IBatchServiceClient">
  <TypeSignature Language="C#" Value="public interface IBatchServiceClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBatchServiceClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IBatchServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBatchServiceClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IBatchServiceClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="60f44-101">Azure Batch のサービスに対する REST 要求の発行用のクライアントです。</span><span class="sxs-lookup"><span data-stu-id="60f44-101">A client for issuing REST requests to the Azure Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="60f44-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Account">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.IAccountOperations Account { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.IAccountOperations Account" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Account" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Account As IAccountOperations" />
      <MemberSignature Language="F#" Value="member this.Account : Microsoft.Azure.Batch.Protocol.IAccountOperations" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Account" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.IAccountOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-103">IAccountOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f44-103">Gets the IAccountOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-104">クライアント API のバージョン。</span><span class="sxs-lookup"><span data-stu-id="60f44-104">Client API Version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Application">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.IApplicationOperations Application { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.IApplicationOperations Application" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Application" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Application As IApplicationOperations" />
      <MemberSignature Language="F#" Value="member this.Application : Microsoft.Azure.Batch.Protocol.IApplicationOperations" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Application" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.IApplicationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-105">IApplicationOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f44-105">Gets the IApplicationOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-106">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="60f44-106">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.ICertificateOperations Certificate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.ICertificateOperations Certificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Certificate As ICertificateOperations" />
      <MemberSignature Language="F#" Value="member this.Certificate : Microsoft.Azure.Batch.Protocol.ICertificateOperations" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Certificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.ICertificateOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-107">ICertificateOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f44-107">Gets the ICertificateOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeNode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.IComputeNodeOperations ComputeNode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations ComputeNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.ComputeNode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeNode As IComputeNodeOperations" />
      <MemberSignature Language="F#" Value="member this.ComputeNode : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.ComputeNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.IComputeNodeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-108">IComputeNodeOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f44-108">Gets the IComputeNodeOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-109">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="60f44-109">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-110">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="60f44-110">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="File">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.IFileOperations File { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.IFileOperations File" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.File" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property File As IFileOperations" />
      <MemberSignature Language="F#" Value="member this.File : Microsoft.Azure.Batch.Protocol.IFileOperations" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.File" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.IFileOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-111">IFileOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f44-111">Gets the IFileOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-112">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="60f44-112">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="60f44-113">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="60f44-113">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Job">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.IJobOperations Job { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.IJobOperations Job" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Job" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Job As IJobOperations" />
      <MemberSignature Language="F#" Value="member this.Job : Microsoft.Azure.Batch.Protocol.IJobOperations" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Job" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.IJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-114">IJobOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f44-114">Gets the IJobOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.IJobScheduleOperations JobSchedule { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations JobSchedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.JobSchedule" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobSchedule As IJobScheduleOperations" />
      <MemberSignature Language="F#" Value="member this.JobSchedule : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.JobSchedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.IJobScheduleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-115">IJobScheduleOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f44-115">Gets the IJobScheduleOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-116">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="60f44-116">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="60f44-117">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="60f44-117">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.IPoolOperations Pool { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.IPoolOperations Pool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Pool" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Pool As IPoolOperations" />
      <MemberSignature Language="F#" Value="member this.Pool : Microsoft.Azure.Batch.Protocol.IPoolOperations" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Pool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.IPoolOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-118">IPoolOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f44-118">Gets the IPoolOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-119">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="60f44-119">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Task">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.ITaskOperations Task { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.ITaskOperations Task" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Task" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Task As ITaskOperations" />
      <MemberSignature Language="F#" Value="member this.Task : Microsoft.Azure.Batch.Protocol.ITaskOperations" Usage="Microsoft.Azure.Batch.Protocol.IBatchServiceClient.Task" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.ITaskOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60f44-120">ITaskOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f44-120">Gets the ITaskOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>