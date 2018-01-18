<Type Name="IServiceBusManagementClient" FullName="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient">
  <TypeSignature Language="C#" Value="public interface IServiceBusManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceBusManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceBusManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IServiceBusManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="0c240-101">Azure Service Bus クライアント</span><span class="sxs-lookup"><span data-stu-id="0c240-101">Azure Service Bus client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="0c240-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-103">クライアント API のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="0c240-103">Client API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-104">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="0c240-104">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-105">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="0c240-105">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-106">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="0c240-106">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisasterRecoveryConfigs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations DisasterRecoveryConfigs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations DisasterRecoveryConfigs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.DisasterRecoveryConfigs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisasterRecoveryConfigs As IDisasterRecoveryConfigsOperations" />
      <MemberSignature Language="F#" Value="member this.DisasterRecoveryConfigs : Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.DisasterRecoveryConfigs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.IDisasterRecoveryConfigsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-107">IDisasterRecoveryConfigsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c240-107">Gets the IDisasterRecoveryConfigsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.IEventHubsOperations EventHubs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.IEventHubsOperations EventHubs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.EventHubs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubs As IEventHubsOperations" />
      <MemberSignature Language="F#" Value="member this.EventHubs : Microsoft.Azure.Management.ServiceBus.IEventHubsOperations" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.EventHubs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.IEventHubsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-108">IEventHubsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c240-108">Gets the IEventHubsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-109">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="0c240-109">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="0c240-110">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="0c240-110">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-111">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="0c240-111">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="0c240-112">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="0c240-112">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Namespaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.INamespacesOperations Namespaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.INamespacesOperations Namespaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Namespaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Namespaces As INamespacesOperations" />
      <MemberSignature Language="F#" Value="member this.Namespaces : Microsoft.Azure.Management.ServiceBus.INamespacesOperations" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Namespaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.INamespacesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-113">INamespacesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c240-113">Gets the INamespacesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.ServiceBus.IOperations" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-114">IOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c240-114">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PremiumMessagingRegions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.IPremiumMessagingRegionsOperations PremiumMessagingRegions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.IPremiumMessagingRegionsOperations PremiumMessagingRegions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.PremiumMessagingRegions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PremiumMessagingRegions As IPremiumMessagingRegionsOperations" />
      <MemberSignature Language="F#" Value="member this.PremiumMessagingRegions : Microsoft.Azure.Management.ServiceBus.IPremiumMessagingRegionsOperations" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.PremiumMessagingRegions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.IPremiumMessagingRegionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-115">IPremiumMessagingRegionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c240-115">Gets the IPremiumMessagingRegionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Queues">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.IQueuesOperations Queues { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.IQueuesOperations Queues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Queues" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Queues As IQueuesOperations" />
      <MemberSignature Language="F#" Value="member this.Queues : Microsoft.Azure.Management.ServiceBus.IQueuesOperations" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Queues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.IQueuesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-116">IQueuesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c240-116">Gets the IQueuesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Regions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.IRegionsOperations Regions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.IRegionsOperations Regions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Regions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Regions As IRegionsOperations" />
      <MemberSignature Language="F#" Value="member this.Regions : Microsoft.Azure.Management.ServiceBus.IRegionsOperations" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Regions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.IRegionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-117">IRegionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c240-117">Gets the IRegionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.IRulesOperations Rules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.IRulesOperations Rules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Rules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Rules As IRulesOperations" />
      <MemberSignature Language="F#" Value="member this.Rules : Microsoft.Azure.Management.ServiceBus.IRulesOperations" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Rules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.IRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-118">IRulesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c240-118">Gets the IRulesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-119">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="0c240-119">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-120">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報です。</span><span class="sxs-lookup"><span data-stu-id="0c240-120">Subscription credentials that uniquely identify a Microsoft Azure subscription.</span></span> <span data-ttu-id="0c240-121">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="0c240-121">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subscriptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations Subscriptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations Subscriptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Subscriptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subscriptions As ISubscriptionsOperations" />
      <MemberSignature Language="F#" Value="member this.Subscriptions : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Subscriptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-122">ISubscriptionsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c240-122">Gets the ISubscriptionsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Topics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.ITopicsOperations Topics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.ITopicsOperations Topics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Topics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Topics As ITopicsOperations" />
      <MemberSignature Language="F#" Value="member this.Topics : Microsoft.Azure.Management.ServiceBus.ITopicsOperations" Usage="Microsoft.Azure.Management.ServiceBus.IServiceBusManagementClient.Topics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.ITopicsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c240-123">ITopicsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="0c240-123">Gets the ITopicsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>