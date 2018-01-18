<Type Name="IDataSourcesOperations" FullName="Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations">
  <TypeSignature Language="C#" Value="public interface IDataSourcesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSourcesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSourcesOperations" />
  <TypeSignature Language="F#" Value="type IDataSourcesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b7fa1-101">DataSourcesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-101">DataSourcesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string dataSourceName, Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string dataSourceName, class Microsoft.Azure.Management.OperationalInsights.Models.DataSource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.DataSource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.DataSource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;" Usage="iDataSourcesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, workspaceName, dataSourceName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.DataSource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b7fa1-102">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-102">The name of the resource group to get.</span></span> <span data-ttu-id="b7fa1-103">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-103">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="b7fa1-104">データ ソースを格納する、ログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="b7fa1-104">Name of the Log Analytics Workspace that will contain the datasource</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="b7fa1-105">データ ソースのリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-105">The name of the datasource resource.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b7fa1-106">作成またはデータ ソースを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-106">The parameters required to create or update a datasource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b7fa1-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b7fa1-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b7fa1-109">作成またはデータ ソースを更新します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-109">Create or update a data source.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b7fa1-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b7fa1-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b7fa1-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string dataSourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string dataSourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDataSourcesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, workspaceName, dataSourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b7fa1-113">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-113">The name of the resource group to get.</span></span> <span data-ttu-id="b7fa1-114">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-114">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="b7fa1-115">データ ソースを含むログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-115">Name of the Log Analytics Workspace that contains the datasource.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="b7fa1-116">データ ソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-116">Name of the datasource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b7fa1-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b7fa1-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b7fa1-119">データ ソースのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-119">Deletes a data source instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b7fa1-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b7fa1-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string dataSourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string dataSourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;" Usage="iDataSourcesOperations.GetWithHttpMessagesAsync (resourceGroupName, workspaceName, dataSourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b7fa1-122">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-122">The name of the resource group to get.</span></span> <span data-ttu-id="b7fa1-123">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-123">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="b7fa1-124">データ ソースを含むログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-124">Name of the Log Analytics Workspace that contains the datasource.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="b7fa1-125">データソースの名前</span><span class="sxs-lookup"><span data-stu-id="b7fa1-125">Name of the datasource</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b7fa1-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b7fa1-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b7fa1-128">データ ソース インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-128">Gets a datasource instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b7fa1-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b7fa1-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b7fa1-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;&gt; ListByWorkspaceNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;&gt; ListByWorkspaceNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations.ListByWorkspaceNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByWorkspaceNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;&gt;" Usage="iDataSourcesOperations.ListByWorkspaceNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="b7fa1-132">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-132">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b7fa1-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b7fa1-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b7fa1-135">次のページへのリンクがワークスペース内のデータ ソース インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-135">Gets the first page of data source instances in a workspace with the link to the next page.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b7fa1-136">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-136">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b7fa1-137">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-137">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b7fa1-138">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-138">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;&gt; ListByWorkspaceWithHttpMessagesAsync (Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;&gt; ListByWorkspaceWithHttpMessagesAsync(class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; odataQuery, string resourceGroupName, string workspaceName, string skiptoken, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IDataSourcesOperations.ListByWorkspaceWithHttpMessagesAsync(Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter},System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByWorkspaceWithHttpMessagesAsync : Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt; * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;&gt;" Usage="iDataSourcesOperations.ListByWorkspaceWithHttpMessagesAsync (odataQuery, resourceGroupName, workspaceName, skiptoken, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter&gt;" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="odataQuery">
            <span data-ttu-id="b7fa1-139">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-139">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b7fa1-140">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-140">The name of the resource group to get.</span></span> <span data-ttu-id="b7fa1-141">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-141">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="b7fa1-142">データ ソースを含むワークスペースです。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-142">The workspace that contains the data sources.</span></span>
            </param>
        <param name="skiptoken">
            <span data-ttu-id="b7fa1-143">データ ソース インスタンスのコレクションの開始点です。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-143">Starting point of the collection of data source instances.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b7fa1-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b7fa1-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b7fa1-146">次のページへのリンクがワークスペース内のデータ ソース インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-146">Gets the first page of data source instances in a workspace with the link to the next page.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b7fa1-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b7fa1-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b7fa1-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b7fa1-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>