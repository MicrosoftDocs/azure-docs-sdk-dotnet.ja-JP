<Type Name="IAccessControlRecordsOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations">
  <TypeSignature Language="C#" Value="public interface IAccessControlRecordsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAccessControlRecordsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAccessControlRecordsOperations" />
  <TypeSignature Language="F#" Value="type IAccessControlRecordsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d2d24-101">AccessControlRecordsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="d2d24-101">AccessControlRecordsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string accessControlRecordName, Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string accessControlRecordName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;" Usage="iAccessControlRecordsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (accessControlRecordName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessControlRecordName">
            <span data-ttu-id="d2d24-102">アクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="d2d24-102">The name of the access control record.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d2d24-103">追加または更新するアクセス制御レコード。</span><span class="sxs-lookup"><span data-stu-id="d2d24-103">The access control record to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2d24-104">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="d2d24-104">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="d2d24-105">管理者名</span><span class="sxs-lookup"><span data-stu-id="d2d24-105">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d2d24-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2d24-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2d24-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2d24-108">作成またはアクセス制御レコードを更新します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-108">Creates or Updates an access control record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d2d24-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d2d24-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d2d24-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string accessControlRecordName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string accessControlRecordName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAccessControlRecordsOperations.BeginDeleteWithHttpMessagesAsync (accessControlRecordName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessControlRecordName">
            <span data-ttu-id="d2d24-112">削除するアクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="d2d24-112">The name of the access control record to delete.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2d24-113">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="d2d24-113">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="d2d24-114">管理者名</span><span class="sxs-lookup"><span data-stu-id="d2d24-114">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d2d24-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2d24-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2d24-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2d24-117">アクセス制御レコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-117">Deletes the access control record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d2d24-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d2d24-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string accessControlRecordName, Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string accessControlRecordName, class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;" Usage="iAccessControlRecordsOperations.CreateOrUpdateWithHttpMessagesAsync (accessControlRecordName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessControlRecordName">
            <span data-ttu-id="d2d24-120">アクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="d2d24-120">The name of the access control record.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d2d24-121">追加または更新するアクセス制御レコード。</span><span class="sxs-lookup"><span data-stu-id="d2d24-121">The access control record to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2d24-122">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="d2d24-122">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="d2d24-123">管理者名</span><span class="sxs-lookup"><span data-stu-id="d2d24-123">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d2d24-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2d24-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2d24-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2d24-126">作成またはアクセス制御レコードを更新します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-126">Creates or Updates an access control record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d2d24-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d2d24-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d2d24-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string accessControlRecordName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string accessControlRecordName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAccessControlRecordsOperations.DeleteWithHttpMessagesAsync (accessControlRecordName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessControlRecordName">
            <span data-ttu-id="d2d24-130">削除するアクセス制御レコードの名前。</span><span class="sxs-lookup"><span data-stu-id="d2d24-130">The name of the access control record to delete.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2d24-131">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="d2d24-131">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="d2d24-132">管理者名</span><span class="sxs-lookup"><span data-stu-id="d2d24-132">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d2d24-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2d24-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2d24-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2d24-135">アクセス制御レコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-135">Deletes the access control record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d2d24-136">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-136">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d2d24-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt; GetWithHttpMessagesAsync (string accessControlRecordName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt; GetWithHttpMessagesAsync(string accessControlRecordName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;" Usage="iAccessControlRecordsOperations.GetWithHttpMessagesAsync (accessControlRecordName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessControlRecordName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessControlRecordName">
            <span data-ttu-id="d2d24-138">取得するアクセス制御レコードの名前です。</span><span class="sxs-lookup"><span data-stu-id="d2d24-138">Name of access control record to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d2d24-139">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="d2d24-139">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="d2d24-140">管理者名</span><span class="sxs-lookup"><span data-stu-id="d2d24-140">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d2d24-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2d24-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2d24-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2d24-143">指定したアクセス制御レコード名のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-143">Returns the properties of the specified access control record name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d2d24-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d2d24-145">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-145">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d2d24-146">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-146">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;&gt; ListByManagerWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;&gt; ListByManagerWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IAccessControlRecordsOperations.ListByManagerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByManagerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;&gt;" Usage="iAccessControlRecordsOperations.ListByManagerWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AccessControlRecord&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d2d24-147">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="d2d24-147">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="d2d24-148">管理者名</span><span class="sxs-lookup"><span data-stu-id="d2d24-148">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d2d24-149">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-149">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2d24-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2d24-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2d24-151">マネージャー内のすべてのアクセス制御レコードを取得します。</span><span class="sxs-lookup"><span data-stu-id="d2d24-151">Retrieves all the access control records in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d2d24-152">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d2d24-153">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-153">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d2d24-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d2d24-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>