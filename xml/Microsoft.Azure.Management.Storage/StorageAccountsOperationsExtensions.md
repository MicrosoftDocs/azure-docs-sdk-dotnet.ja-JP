<Type Name="StorageAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0ac6c-101">StorageAccountsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-101">Extension methods for StorageAccountsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount BeginCreate (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount BeginCreate(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As StorageAccountCreateParameters) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-103">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-103">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-104">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-104">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-105">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-105">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-106">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-106">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ac6c-107">作成したアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-107">The parameters to provide for the created account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-108">指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-108">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="0ac6c-109">アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-109">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="0ac6c-110">アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-110">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; BeginCreateAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; BeginCreateAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;BeginCreateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-112">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-112">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-113">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-113">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-114">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-114">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-115">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-115">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ac6c-116">作成したアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-116">The parameters to provide for the created account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-118">指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-118">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="0ac6c-119">アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-119">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="0ac6c-120">アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-120">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult CheckNameAvailability (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult CheckNameAvailability(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As IStorageAccountsOperations, name As String) As CheckNameAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string -&gt; Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailability (operations, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-121">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="0ac6c-122">ストレージ アカウント名。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-122">The storage account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-123">ストレージ アカウント名が有効で既に使用されていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-123">Checks that the storage account name is valid and is not already in use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-124">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="0ac6c-125">ストレージ アカウント名。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-125">The storage account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-127">ストレージ アカウント名が有効で既に使用されていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-127">Checks that the storage account name is valid and is not already in use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount Create (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount Create(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Create(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As StorageAccountCreateParameters) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Create (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-129">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-129">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-130">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-130">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-131">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-131">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-132">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-132">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ac6c-133">作成したアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-133">The parameters to provide for the created account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-134">指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-134">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="0ac6c-135">アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-135">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="0ac6c-136">アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-136">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; CreateAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; CreateAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-138">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-138">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-139">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-139">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-140">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-140">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-141">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-141">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ac6c-142">作成したアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-142">The parameters to provide for the created account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-144">指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-144">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="0ac6c-145">アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-145">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="0ac6c-146">アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-146">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Delete(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Delete (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-147">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-148">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-148">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-149">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-149">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-150">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-150">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-151">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-151">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-152">Microsoft Azure でストレージ アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-152">Deletes a storage account in Microsoft Azure.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-154">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-154">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-155">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-155">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-156">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-156">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-157">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-157">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-159">Microsoft Azure でストレージ アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-159">Deletes a storage account in Microsoft Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount GetProperties (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount GetProperties(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetProperties(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetProperties (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member GetProperties : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetProperties (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-161">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-161">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-162">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-162">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-163">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-163">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-164">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-164">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-165">指定されたストレージ アカウントなどは、name、SKU 名、場所、およびアカウントの状態のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-165">Returns the properties for the specified storage account including but not limited to name, SKU name, location, and account status.</span></span> <span data-ttu-id="0ac6c-166">ListKeys 操作は、記憶域のキーの取得を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-166">The ListKeys operation should be used to retrieve storage keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; GetPropertiesAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; GetPropertiesAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetPropertiesAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.GetPropertiesAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;GetPropertiesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-168">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-168">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-169">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-169">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-170">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-170">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-171">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-171">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-173">指定されたストレージ アカウントなどは、name、SKU 名、場所、およびアカウントの状態のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-173">Returns the properties for the specified storage account including but not limited to name, SKU name, location, and account status.</span></span> <span data-ttu-id="0ac6c-174">ListKeys 操作は、記憶域のキーの取得を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-174">The ListKeys operation should be used to retrieve storage keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; List (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; List(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.List(Microsoft.Azure.Management.Storage.IStorageAccountsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IStorageAccountsOperations) As IEnumerable(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Storage.IStorageAccountsOperations -&gt; seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-175">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-176">サブスクリプションで使用可能なすべてのストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-176">Lists all the storage accounts available under the subscription.</span></span> <span data-ttu-id="0ac6c-177">ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-177">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAccountSAS">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse ListAccountSAS (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse ListAccountSAS(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSAS(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.AccountSasParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAccountSAS (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As AccountSasParameters) As ListAccountSasResponse" />
      <MemberSignature Language="F#" Value="static member ListAccountSAS : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.AccountSasParameters -&gt; Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSAS (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.AccountSasParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-178">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-179">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-179">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-180">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-180">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-181">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-181">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-182">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-182">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ac6c-183">ストレージ アカウントの一覧の SAS の資格情報を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-183">The parameters to provide to list SAS credentials for the storage account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-184">ストレージ アカウントの SAS の資格情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-184">List SAS credentials of a storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAccountSASAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt; ListAccountSASAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt; ListAccountSASAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSASAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.AccountSasParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAccountSASAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.AccountSasParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAccountSASAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListAccountSASAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.AccountSasParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-186">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-186">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-187">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-187">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-188">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-188">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-189">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-189">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ac6c-190">ストレージ アカウントの一覧の SAS の資格情報を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-190">The parameters to provide to list SAS credentials for the storage account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-192">ストレージ アカウントの SAS の資格情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-192">List SAS credentials of a storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-193">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-195">サブスクリプションで使用可能なすべてのストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-195">Lists all the storage accounts available under the subscription.</span></span> <span data-ttu-id="0ac6c-196">ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-196">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; ListByResourceGroup (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; ListByResourceGroup(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IStorageAccountsOperations, resourceGroupName As String) As IEnumerable(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-198">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-198">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-199">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-199">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-200">指定したリソース グループで使用可能なすべてのストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-200">Lists all the storage accounts available under the given resource group.</span></span>
            <span data-ttu-id="0ac6c-201">ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-201">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-202">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-202">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-203">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-203">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-204">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-204">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-206">指定したリソース グループで使用可能なすべてのストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-206">Lists all the storage accounts available under the given resource group.</span></span>
            <span data-ttu-id="0ac6c-207">ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-207">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult ListKeys (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult ListKeys(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeys(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String) As StorageAccountListKeysResult" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeys (operations, resourceGroupName, accountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-209">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-209">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-210">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-210">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-211">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-211">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-212">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-212">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-213">指定されたストレージ アカウントのアクセス キーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-213">Lists the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; ListKeysAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; ListKeysAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListKeysAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-215">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-215">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-216">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-216">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-217">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-217">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-218">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-218">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-220">指定されたストレージ アカウントのアクセス キーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-220">Lists the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceSAS">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse ListServiceSAS (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse ListServiceSAS(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSAS(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.ServiceSasParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListServiceSAS (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As ServiceSasParameters) As ListServiceSasResponse" />
      <MemberSignature Language="F#" Value="static member ListServiceSAS : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.ServiceSasParameters -&gt; Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSAS (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-222">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-222">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-223">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-223">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-224">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-224">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-225">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-225">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ac6c-226">リスト サービスの SAS の資格情報を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-226">The parameters to provide to list service SAS credentials.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-227">特定のリソースのサービスの SAS 資格情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-227">List service SAS credentials of a specific resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceSASAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt; ListServiceSASAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt; ListServiceSASAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSASAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.ServiceSasParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListServiceSASAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.ServiceSasParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.ListServiceSASAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;ListServiceSASAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-228">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-228">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-229">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-229">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-230">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-230">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-231">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-231">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-232">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-232">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ac6c-233">リスト サービスの SAS の資格情報を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-233">The parameters to provide to list service SAS credentials.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-235">特定のリソースのサービスの SAS 資格情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-235">List service SAS credentials of a specific resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult RegenerateKey (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult RegenerateKey(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, keyName As String) As StorageAccountListKeysResult" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * string -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKey (operations, resourceGroupName, accountName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-237">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-237">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-238">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-238">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-239">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-239">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-240">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-240">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="0ac6c-241">再生成された、可能な値を許可する記憶域のキーの名前は、key1、key2 です。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-241">The name of storage keys that want to be regenerated, possible vaules are key1, key2.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-242">指定されたストレージ アカウントのアクセス キーの 1 つを再生成します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-242">Regenerates one of the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-244">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-244">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-245">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-245">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-246">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-246">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-247">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-247">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="0ac6c-248">再生成された、可能な値を許可する記憶域のキーの名前は、key1、key2 です。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-248">The name of storage keys that want to be regenerated, possible vaules are key1, key2.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-250">指定されたストレージ アカウントのアクセス キーの 1 つを再生成します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-250">Regenerates one of the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Storage.Models.StorageAccount Update (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Storage.Models.StorageAccount Update(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Update(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, parameters As StorageAccountUpdateParameters) As StorageAccount" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.Update (operations, resourceGroupName, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.StorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-251">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-251">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-252">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-252">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-253">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-253">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-254">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-254">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-255">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-255">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ac6c-256">更新されたアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-256">The parameters to provide for the updated account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-257">更新操作は、SKU、暗号化、アクセス層、またはストレージ アカウント用のタグの更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-257">The update operation can be used to update the SKU, encryption, access tier, or tags for a storage account.</span></span> <span data-ttu-id="0ac6c-258">カスタム ドメインにアカウントをマップにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-258">It can also be used to map the account to a custom domain.</span></span> <span data-ttu-id="0ac6c-259">ストレージ アカウントごとに 1 つのカスタム ドメインがサポートされます。カスタム ドメインの置換と変更はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-259">Only one custom domain is supported per storage account; the replacement/change of custom domain is not supported.</span></span> <span data-ttu-id="0ac6c-260">古いカスタム ドメインを置換するために古い値でなければなりませんクリア未登録の新しい値を設定する前に。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-260">In order to replace an old custom domain, the old value must be cleared/unregistered before a new value can be set.</span></span> <span data-ttu-id="0ac6c-261">複数のプロパティの更新はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-261">The update of multiple properties is supported.</span></span> <span data-ttu-id="0ac6c-262">この呼び出しでは、ストレージ アカウントのキーは変更されません。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-262">This call does not change the storage keys for the account.</span></span> <span data-ttu-id="0ac6c-263">ストレージ アカウント キーを変更する場合は、再生成のキー操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-263">If you want to change the storage account keys, use the regenerate keys operation.</span></span> <span data-ttu-id="0ac6c-264">作成後は、ストレージ アカウントの名前と場所を変更できません。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-264">The location and name of the storage account cannot be changed after creation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; UpdateAsync (this Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt; UpdateAsync(class Microsoft.Azure.Management.Storage.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Storage.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Storage.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;" Usage="Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.StorageAccountsOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0ac6c-265">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-265">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0ac6c-266">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-266">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="0ac6c-267">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-267">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="0ac6c-268">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-268">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="0ac6c-269">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-269">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0ac6c-270">更新されたアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-270">The parameters to provide for the updated account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0ac6c-271">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0ac6c-272">更新操作は、SKU、暗号化、アクセス層、またはストレージ アカウント用のタグの更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-272">The update operation can be used to update the SKU, encryption, access tier, or tags for a storage account.</span></span> <span data-ttu-id="0ac6c-273">カスタム ドメインにアカウントをマップにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-273">It can also be used to map the account to a custom domain.</span></span> <span data-ttu-id="0ac6c-274">ストレージ アカウントごとに 1 つのカスタム ドメインがサポートされます。カスタム ドメインの置換と変更はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-274">Only one custom domain is supported per storage account; the replacement/change of custom domain is not supported.</span></span> <span data-ttu-id="0ac6c-275">古いカスタム ドメインを置換するために古い値でなければなりませんクリア未登録の新しい値を設定する前に。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-275">In order to replace an old custom domain, the old value must be cleared/unregistered before a new value can be set.</span></span> <span data-ttu-id="0ac6c-276">複数のプロパティの更新はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-276">The update of multiple properties is supported.</span></span> <span data-ttu-id="0ac6c-277">この呼び出しでは、ストレージ アカウントのキーは変更されません。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-277">This call does not change the storage keys for the account.</span></span> <span data-ttu-id="0ac6c-278">ストレージ アカウント キーを変更する場合は、再生成のキー操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-278">If you want to change the storage account keys, use the regenerate keys operation.</span></span> <span data-ttu-id="0ac6c-279">作成後は、ストレージ アカウントの名前と場所を変更できません。</span><span class="sxs-lookup"><span data-stu-id="0ac6c-279">The location and name of the storage account cannot be changed after creation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>