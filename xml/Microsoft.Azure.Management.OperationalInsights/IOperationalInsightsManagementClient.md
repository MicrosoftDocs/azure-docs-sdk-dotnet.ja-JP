<Type Name="IOperationalInsightsManagementClient" FullName="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient">
  <TypeSignature Language="C#" Value="public interface IOperationalInsightsManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperationalInsightsManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperationalInsightsManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IOperationalInsightsManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="7f3e9-101">Azure Operational Insights の REST API の .Net クライアント ラッパー</span><span class="sxs-lookup"><span data-stu-id="7f3e9-101">.Net client wrapper for the REST API for Azure Operational Insights</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-103">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-103">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-104">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-104">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSources">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations DataSources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations DataSources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.DataSources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSources As IDataSourcesOperations" />
      <MemberSignature Language="F#" Value="member this.DataSources : Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.DataSources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-105">IDataSourcesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-105">Gets the IDataSourcesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-106">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-106">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-107">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-107">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="7f3e9-108">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-108">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations LinkedServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations LinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.LinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LinkedServices As ILinkedServicesOperations" />
      <MemberSignature Language="F#" Value="member this.LinkedServices : Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.LinkedServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-109">ILinkedServicesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-109">Gets the ILinkedServicesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-110">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-110">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="7f3e9-111">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-111">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SavedSearches">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations SavedSearches { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations SavedSearches" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.SavedSearches" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SavedSearches As ISavedSearchesOperations" />
      <MemberSignature Language="F#" Value="member this.SavedSearches : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.SavedSearches" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-112">ISavedSearchesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-112">Gets the ISavedSearchesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-113">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-113">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageInsights">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations StorageInsights { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations StorageInsights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.StorageInsights" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageInsights As IStorageInsightsOperations" />
      <MemberSignature Language="F#" Value="member this.StorageInsights : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.StorageInsights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-114">IStorageInsightsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-114">Gets the IStorageInsightsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-115">Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-115">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="7f3e9-116">サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-116">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Workspaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations Workspaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations Workspaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.Workspaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Workspaces As IWorkspacesOperations" />
      <MemberSignature Language="F#" Value="member this.Workspaces : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" Usage="Microsoft.Azure.Management.OperationalInsights.IOperationalInsightsManagementClient.Workspaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f3e9-117">IWorkspacesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="7f3e9-117">Gets the IWorkspacesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>