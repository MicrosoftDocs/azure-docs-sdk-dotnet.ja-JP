<Type Name="IStreamAnalyticsManagementClient" FullName="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient">
  <TypeSignature Language="C#" Value="public interface IStreamAnalyticsManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStreamAnalyticsManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStreamAnalyticsManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IStreamAnalyticsManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="40019-101">Stream Analytics クライアント</span><span class="sxs-lookup"><span data-stu-id="40019-101">Stream Analytics Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="40019-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-103">クライアント Api のバージョン。</span><span class="sxs-lookup"><span data-stu-id="40019-103">Client Api Version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-104">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="40019-104">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-105">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="40019-105">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-106">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="40019-106">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Functions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations Functions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations Functions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Functions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Functions As IFunctionsOperations" />
      <MemberSignature Language="F#" Value="member this.Functions : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Functions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-107">IFunctionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="40019-107">Gets the IFunctionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-108">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="40019-108">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="40019-109">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="40019-109">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inputs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.IInputsOperations Inputs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations Inputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Inputs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Inputs As IInputsOperations" />
      <MemberSignature Language="F#" Value="member this.Inputs : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Inputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.IInputsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-110">IInputsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="40019-110">Gets the IInputsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-111">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="40019-111">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="40019-112">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="40019-112">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.StreamAnalytics.IOperations" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-113">IOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="40019-113">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations Outputs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations Outputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Outputs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Outputs As IOutputsOperations" />
      <MemberSignature Language="F#" Value="member this.Outputs : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Outputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-114">IOutputsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="40019-114">Gets the IOutputsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-115">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="40019-115">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamingJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations StreamingJobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations StreamingJobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.StreamingJobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StreamingJobs As IStreamingJobsOperations" />
      <MemberSignature Language="F#" Value="member this.StreamingJobs : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.StreamingJobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-116">IStreamingJobsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="40019-116">Gets the IStreamingJobsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-117">Microsoft Azure サブスクリプションを一意に識別する GUID です。</span><span class="sxs-lookup"><span data-stu-id="40019-117">GUID which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="40019-118">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="40019-118">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subscriptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.ISubscriptionsOperations Subscriptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.ISubscriptionsOperations Subscriptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Subscriptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subscriptions As ISubscriptionsOperations" />
      <MemberSignature Language="F#" Value="member this.Subscriptions : Microsoft.Azure.Management.StreamAnalytics.ISubscriptionsOperations" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Subscriptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.ISubscriptionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-119">ISubscriptionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="40019-119">Gets the ISubscriptionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transformations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations Transformations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations Transformations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Transformations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transformations As ITransformationsOperations" />
      <MemberSignature Language="F#" Value="member this.Transformations : Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" Usage="Microsoft.Azure.Management.StreamAnalytics.IStreamAnalyticsManagementClient.Transformations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40019-120">ITransformationsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="40019-120">Gets the ITransformationsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>