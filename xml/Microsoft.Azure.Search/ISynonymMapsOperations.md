<Type Name="ISynonymMapsOperations" FullName="Microsoft.Azure.Search.ISynonymMapsOperations">
  <TypeSignature Language="C#" Value="public interface ISynonymMapsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISynonymMapsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.ISynonymMapsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISynonymMapsOperations" />
  <TypeSignature Language="F#" Value="type ISynonymMapsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e273b-101">SynonymMapsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="e273b-101">SynonymMapsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.ISynonymMapsOperations.CreateOrUpdateWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt;" Usage="iSynonymMapsOperations.CreateOrUpdateWithHttpMessagesAsync (synonymMap, searchRequestOptions, accessCondition, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="synonymMap">
            <span data-ttu-id="e273b-102">作成または更新 synonymmap の定義。</span><span class="sxs-lookup"><span data-stu-id="e273b-102">The definition of the synonymmap to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e273b-103">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e273b-103">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="e273b-104">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e273b-104">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e273b-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e273b-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e273b-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e273b-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e273b-107">新しい Azure Search synonymmap を作成または、既に存在する場合に、synonymmap を更新します。</span><span class="sxs-lookup"><span data-stu-id="e273b-107">Creates a new Azure Search synonymmap or updates a synonymmap if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string synonymMapName, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string synonymMapName, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.ISynonymMapsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt;" Usage="iSynonymMapsOperations.CreateOrUpdateWithHttpMessagesAsync (synonymMapName, synonymMap, searchRequestOptions, accessCondition, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="synonymMapName">
            <span data-ttu-id="e273b-108">作成または更新するシノニム マップの名前。</span><span class="sxs-lookup"><span data-stu-id="e273b-108">The name of the synonym map to create or update.</span></span>
            </param>
        <param name="synonymMap">
            <span data-ttu-id="e273b-109">マップの定義、シノニムを作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="e273b-109">The definition of the synonym map to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e273b-110">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e273b-110">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="e273b-111">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e273b-111">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e273b-112">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e273b-112">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e273b-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e273b-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e273b-114">新しい Azure Search シノニム マップを作成または、既に存在する場合は、シノニム マップを更新します。</span><span class="sxs-lookup"><span data-stu-id="e273b-114">Creates a new Azure Search synonym map or updates a synonym map if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e273b-115">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-115">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e273b-116">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-116">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e273b-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt; CreateWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt;&gt; CreateWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.ISynonymMapsOperations.CreateWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt;" Usage="iSynonymMapsOperations.CreateWithHttpMessagesAsync (synonymMap, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="synonymMap">
            <span data-ttu-id="e273b-118">作成するシノニム マップの定義。</span><span class="sxs-lookup"><span data-stu-id="e273b-118">The definition of the synonym map to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e273b-119">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e273b-119">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e273b-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e273b-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e273b-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e273b-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e273b-122">新しい Azure Search シノニム マップを作成します。</span><span class="sxs-lookup"><span data-stu-id="e273b-122">Creates a new Azure Search synonym map.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e273b-123">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-123">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e273b-124">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-124">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e273b-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.ISynonymMapsOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSynonymMapsOperations.DeleteWithHttpMessagesAsync (synonymMapName, searchRequestOptions, accessCondition, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="synonymMapName">
            <span data-ttu-id="e273b-126">削除するシノニム マップの名前。</span><span class="sxs-lookup"><span data-stu-id="e273b-126">The name of the synonym map to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e273b-127">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e273b-127">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="e273b-128">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e273b-128">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e273b-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e273b-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e273b-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e273b-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e273b-131">Azure Search シノニム マップを削除します。</span><span class="sxs-lookup"><span data-stu-id="e273b-131">Deletes an Azure Search synonym map.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e273b-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e273b-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; ExistsWithHttpMessagesAsync (string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; ExistsWithHttpMessagesAsync(string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.ISynonymMapsOperations.ExistsWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iSynonymMapsOperations.ExistsWithHttpMessagesAsync (synonymMapName, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="synonymMapName">
            <span data-ttu-id="e273b-134">シノニムのマップの名前。</span><span class="sxs-lookup"><span data-stu-id="e273b-134">The name of the synonym map.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e273b-135">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e273b-135">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e273b-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e273b-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e273b-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e273b-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e273b-138">シノニムの指定したマップは、Azure Search サービスで存在するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="e273b-138">Determines whether or not the given synonym map exists in the Azure Search service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e273b-139">値を含む応答<c>true</c>シノニム マップが存在する場合<c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="e273b-139">A response with the value <c>true</c> if the synonym map exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt; GetWithHttpMessagesAsync (string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt;&gt; GetWithHttpMessagesAsync(string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.ISynonymMapsOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt;" Usage="iSynonymMapsOperations.GetWithHttpMessagesAsync (synonymMapName, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="synonymMapName">
            <span data-ttu-id="e273b-140">取得するシノニム マップの名前。</span><span class="sxs-lookup"><span data-stu-id="e273b-140">The name of the synonym map to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e273b-141">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e273b-141">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e273b-142">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e273b-142">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e273b-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e273b-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e273b-144">Azure Search からシノニム マップの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="e273b-144">Retrieves a synonym map definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e273b-145">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-145">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e273b-146">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-146">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e273b-147">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMapListResult&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.SynonymMapListResult&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.ISynonymMapsOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMapListResult&gt;&gt;" Usage="iSynonymMapsOperations.ListWithHttpMessagesAsync (searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.SynonymMapListResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchRequestOptions">
            <span data-ttu-id="e273b-148">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e273b-148">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e273b-149">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e273b-149">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e273b-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e273b-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e273b-151">Azure Search サービスの使用可能なシノニムのマップをすべて一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e273b-151">Lists all synonym maps available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Synonym-Maps" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e273b-152">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e273b-153">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-153">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e273b-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e273b-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>