<Type Name="ISavedSearchesOperations" FullName="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations">
  <TypeSignature Language="C#" Value="public interface ISavedSearchesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISavedSearchesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISavedSearchesOperations" />
  <TypeSignature Language="F#" Value="type ISavedSearchesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="32364-101">SavedSearchesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="32364-101">SavedSearchesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string savedSearchName, Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string savedSearchName, class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;&gt;" Usage="iSavedSearchesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, workspaceName, savedSearchName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="32364-102">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="32364-102">The name of the resource group to get.</span></span> <span data-ttu-id="32364-103">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="32364-103">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="32364-104">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="32364-104">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="32364-105">保存された検索の id。</span><span class="sxs-lookup"><span data-stu-id="32364-105">The id of the saved search.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="32364-106">検索の保存に必要なパラメーター。</span><span class="sxs-lookup"><span data-stu-id="32364-106">The parameters required to save a search.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="32364-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="32364-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32364-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32364-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32364-109">作成するか、特定のワークスペースの保存された検索を更新します。</span><span class="sxs-lookup"><span data-stu-id="32364-109">Creates or updates a saved search for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="32364-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="32364-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="32364-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string savedSearchName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string savedSearchName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSavedSearchesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, workspaceName, savedSearchName, customHeaders, cancellationToken)" />
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
        <Parameter Name="savedSearchName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="32364-113">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="32364-113">The name of the resource group to get.</span></span> <span data-ttu-id="32364-114">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="32364-114">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="32364-115">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="32364-115">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="32364-116">保存された検索の名前です。</span><span class="sxs-lookup"><span data-stu-id="32364-116">Name of the saved search.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="32364-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="32364-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32364-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32364-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32364-119">任意のワークスペースに指定した保存済み検索を削除します。</span><span class="sxs-lookup"><span data-stu-id="32364-119">Deletes the specified saved search in a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="32364-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="32364-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetResultsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt; GetResultsWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string savedSearchName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt; GetResultsWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string savedSearchName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations.GetResultsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetResultsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt;" Usage="iSavedSearchesOperations.GetResultsWithHttpMessagesAsync (resourceGroupName, workspaceName, savedSearchName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="32364-122">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="32364-122">The name of the resource group to get.</span></span> <span data-ttu-id="32364-123">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="32364-123">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="32364-124">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="32364-124">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="32364-125">保存された検索の名前。</span><span class="sxs-lookup"><span data-stu-id="32364-125">The name of the saved search.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="32364-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="32364-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32364-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32364-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32364-128">任意のワークスペースに保存された検索結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="32364-128">Gets the results from a saved search for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="32364-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="32364-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="32364-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string savedSearchName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string savedSearchName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;&gt;" Usage="iSavedSearchesOperations.GetWithHttpMessagesAsync (resourceGroupName, workspaceName, savedSearchName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="32364-132">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="32364-132">The name of the resource group to get.</span></span> <span data-ttu-id="32364-133">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="32364-133">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="32364-134">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="32364-134">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="32364-135">保存された検索の id。</span><span class="sxs-lookup"><span data-stu-id="32364-135">The id of the saved search.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="32364-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="32364-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32364-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32364-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32364-138">特定のワークスペースの指定した保存済み検索を取得します。</span><span class="sxs-lookup"><span data-stu-id="32364-138">Gets the specified saved search for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="32364-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="32364-140">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-140">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="32364-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult&gt;&gt; ListByWorkspaceWithHttpMessagesAsync (string resourceGroupName, string workspaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult&gt;&gt; ListByWorkspaceWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations.ListByWorkspaceWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByWorkspaceWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult&gt;&gt;" Usage="iSavedSearchesOperations.ListByWorkspaceWithHttpMessagesAsync (resourceGroupName, workspaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="32364-142">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="32364-142">The name of the resource group to get.</span></span> <span data-ttu-id="32364-143">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="32364-143">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="32364-144">ログ分析ワークスペース名</span><span class="sxs-lookup"><span data-stu-id="32364-144">Log Analytics workspace name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="32364-145">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="32364-145">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32364-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32364-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32364-147">指定されたログ分析ワークスペースの保存された検索を取得します。</span><span class="sxs-lookup"><span data-stu-id="32364-147">Gets the saved searches for a given Log Analytics Workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="32364-148">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-148">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="32364-149">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-149">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="32364-150">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32364-150">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>