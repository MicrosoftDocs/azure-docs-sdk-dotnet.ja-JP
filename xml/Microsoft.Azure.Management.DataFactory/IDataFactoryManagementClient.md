<Type Name="IDataFactoryManagementClient" FullName="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient">
  <TypeSignature Language="C#" Value="public interface IDataFactoryManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataFactoryManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataFactoryManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IDataFactoryManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c652c-101">Azure データ ファクトリ V2 管理 API は、Azure データ ファクトリ V2 サービスと web サービスを操作の RESTful セットを提供します。</span><span class="sxs-lookup"><span data-stu-id="c652c-101">The Azure Data Factory V2 management API provides a RESTful set of web services that interact with Azure Data Factory V2 services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="c652c-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityRuns">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IActivityRunsOperations ActivityRuns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IActivityRunsOperations ActivityRuns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.ActivityRuns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityRuns As IActivityRunsOperations" />
      <MemberSignature Language="F#" Value="member this.ActivityRuns : Microsoft.Azure.Management.DataFactory.IActivityRunsOperations" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.ActivityRuns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IActivityRunsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-103">IActivityRunsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c652c-103">Gets the IActivityRunsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-104">API のバージョン。</span><span class="sxs-lookup"><span data-stu-id="c652c-104">The API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-105">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="c652c-105">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-106">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="c652c-106">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IDatasetsOperations Datasets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IDatasetsOperations Datasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Datasets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Datasets As IDatasetsOperations" />
      <MemberSignature Language="F#" Value="member this.Datasets : Microsoft.Azure.Management.DataFactory.IDatasetsOperations" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Datasets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IDatasetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-107">IDatasetsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c652c-107">Gets the IDatasetsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-108">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="c652c-108">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Factories">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IFactoriesOperations Factories { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IFactoriesOperations Factories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Factories" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Factories As IFactoriesOperations" />
      <MemberSignature Language="F#" Value="member this.Factories : Microsoft.Azure.Management.DataFactory.IFactoriesOperations" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Factories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IFactoriesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-109">IFactoriesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c652c-109">Gets the IFactoriesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-110">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="c652c-110">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="c652c-111">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="c652c-111">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntegrationRuntimeNodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations IntegrationRuntimeNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations IntegrationRuntimeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.IntegrationRuntimeNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IntegrationRuntimeNodes As IIntegrationRuntimeNodesOperations" />
      <MemberSignature Language="F#" Value="member this.IntegrationRuntimeNodes : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.IntegrationRuntimeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IIntegrationRuntimeNodesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-112">IIntegrationRuntimeNodesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c652c-112">Gets the IIntegrationRuntimeNodesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntegrationRuntimes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations IntegrationRuntimes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations IntegrationRuntimes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.IntegrationRuntimes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IntegrationRuntimes As IIntegrationRuntimesOperations" />
      <MemberSignature Language="F#" Value="member this.IntegrationRuntimes : Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.IntegrationRuntimes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IIntegrationRuntimesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-113">IIntegrationRuntimesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c652c-113">Gets the IIntegrationRuntimesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations LinkedServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations LinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.LinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LinkedServices As ILinkedServicesOperations" />
      <MemberSignature Language="F#" Value="member this.LinkedServices : Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.LinkedServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-114">ILinkedServicesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c652c-114">Gets the ILinkedServicesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-115">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="c652c-115">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="c652c-116">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="c652c-116">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IOperations Operations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IOperations Operations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Operations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operations As IOperations" />
      <MemberSignature Language="F#" Value="member this.Operations : Microsoft.Azure.Management.DataFactory.IOperations" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Operations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-117">IOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c652c-117">Gets the IOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineRuns">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations PipelineRuns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations PipelineRuns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.PipelineRuns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineRuns As IPipelineRunsOperations" />
      <MemberSignature Language="F#" Value="member this.PipelineRuns : Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.PipelineRuns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IPipelineRunsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-118">IPipelineRunsOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c652c-118">Gets the IPipelineRunsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pipelines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.IPipelinesOperations Pipelines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.IPipelinesOperations Pipelines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Pipelines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Pipelines As IPipelinesOperations" />
      <MemberSignature Language="F#" Value="member this.Pipelines : Microsoft.Azure.Management.DataFactory.IPipelinesOperations" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Pipelines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.IPipelinesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-119">IPipelinesOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c652c-119">Gets the IPipelinesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-120">取得または json のシリアル化設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="c652c-120">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-121">サブスクリプションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="c652c-121">The subscription identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Triggers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.ITriggersOperations Triggers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.ITriggersOperations Triggers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Triggers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Triggers As ITriggersOperations" />
      <MemberSignature Language="F#" Value="member this.Triggers : Microsoft.Azure.Management.DataFactory.ITriggersOperations" Usage="Microsoft.Azure.Management.DataFactory.IDataFactoryManagementClient.Triggers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.ITriggersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c652c-122">ITriggersOperations を取得します。</span><span class="sxs-lookup"><span data-stu-id="c652c-122">Gets the ITriggersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>