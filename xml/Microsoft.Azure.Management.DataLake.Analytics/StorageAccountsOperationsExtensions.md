<Type Name="StorageAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="51836-101">StorageAccountsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="51836-101">Extension methods for StorageAccountsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static void Add (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Add(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Add(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Add (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, parameters As AddStorageAccountParameters)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Add (operations, resourceGroupName, accountName, storageAccountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-103">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-103">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-104">Azure ストレージ アカウントを追加する、Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-104">The name of the Data Lake Analytics account to which to add the Azure Storage account.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-105">追加する Azure ストレージ アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="51836-105">The name of the Azure Storage account to add</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51836-106">Azure ストレージ アカウントのアクセス キーと省略可能なサフィックスを含むパラメーター。</span><span class="sxs-lookup"><span data-stu-id="51836-106">The parameters containing the access key and optional suffix for the Azure Storage Account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-107">Azure ストレージ アカウントを追加する指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="51836-107">Updates the specified Data Lake Analytics account to add an Azure Storage account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AddAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AddAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.AddAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.AddAsync (operations, resourceGroupName, accountName, storageAccountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-109">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-109">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-110">Azure ストレージ アカウントを追加する、Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-110">The name of the Data Lake Analytics account to which to add the Azure Storage account.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-111">追加する Azure ストレージ アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="51836-111">The name of the Azure Storage account to add</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51836-112">Azure ストレージ アカウントのアクセス キーと省略可能なサフィックスを含むパラメーター。</span><span class="sxs-lookup"><span data-stu-id="51836-112">The parameters containing the access key and optional suffix for the Azure Storage Account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-114">Azure ストレージ アカウントを追加する指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="51836-114">Updates the specified Data Lake Analytics account to add an Azure Storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Delete (operations, resourceGroupName, accountName, storageAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-116">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-116">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-117">Azure ストレージ アカウントを削除する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-117">The name of the Data Lake Analytics account from which to remove the Azure Storage account.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-118">削除する Azure ストレージ アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="51836-118">The name of the Azure Storage account to remove</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-119">Azure ストレージ アカウントを削除する指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="51836-119">Updates the specified Data Lake Analytics account to remove an Azure Storage account.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-121">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-121">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-122">Azure ストレージ アカウントを削除する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-122">The name of the Data Lake Analytics account from which to remove the Azure Storage account.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-123">削除する Azure ストレージ アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="51836-123">The name of the Azure Storage account to remove</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-125">Azure ストレージ アカウントを削除する指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="51836-125">Updates the specified Data Lake Analytics account to remove an Azure Storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo Get (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo Get(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String) As StorageAccountInfo" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Get (operations, resourceGroupName, accountName, storageAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-127">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-127">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-128">Azure ストレージ アカウントの詳細を取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-128">The name of the Data Lake Analytics account from which to retrieve Azure storage account details.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-129">詳細を取得する対象の Azure ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-129">The name of the Azure Storage account for which to retrieve the details.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-130">指定された Azure ストレージ アカウントが指定された Data Lake Analytics アカウントへのリンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-130">Gets the specified Azure Storage account linked to the given Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-132">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-132">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-133">Azure ストレージ アカウントの詳細を取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-133">The name of the Data Lake Analytics account from which to retrieve Azure storage account details.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-134">詳細を取得する対象の Azure ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-134">The name of the Azure Storage account for which to retrieve the details.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-136">指定された Azure ストレージ アカウントが指定された Data Lake Analytics アカウントへのリンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-136">Gets the specified Azure Storage account linked to the given Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageContainer">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer GetStorageContainer (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer GetStorageContainer(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainer(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStorageContainer (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, containerName As String) As StorageContainer" />
      <MemberSignature Language="F#" Value="static member GetStorageContainer : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainer (operations, resourceGroupName, accountName, storageAccountName, containerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-138">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-138">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-139">Blob コンテナーを取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-139">The name of the Data Lake Analytics account for which to retrieve blob container.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-140">Blob コンテナーを取得する対象の Azure ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-140">The name of the Azure storage account from which to retrieve the blob container.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="51836-141">取得する Azure ストレージ コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="51836-141">The name of the Azure storage container to retrieve</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-142">指定された Data Lake Analytics と Azure ストレージ アカウントに関連付けられている指定された Azure ストレージ コンテナーを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-142">Gets the specified Azure Storage container associated with the given Data Lake Analytics and Azure Storage accounts.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageContainerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; GetStorageContainerAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; GetStorageContainerAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainerAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageContainerAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainerAsync (operations, resourceGroupName, accountName, storageAccountName, containerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;GetStorageContainerAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-144">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-144">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-145">Blob コンテナーを取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-145">The name of the Data Lake Analytics account for which to retrieve blob container.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-146">Blob コンテナーを取得する対象の Azure ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-146">The name of the Azure storage account from which to retrieve the blob container.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="51836-147">取得する Azure ストレージ コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="51836-147">The name of the Azure storage container to retrieve</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-149">指定された Data Lake Analytics と Azure ストレージ アカウントに関連付けられている指定された Azure ストレージ コンテナーを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-149">Gets the specified Azure Storage container associated with the given Data Lake Analytics and Azure Storage accounts.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, Optional odataQuery As ODataQuery(Of StorageAccountInfo) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of StorageAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-151">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-151">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-152">名前、Data Lake Analytics アカウントを Azure ストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="51836-152">The name of the Data Lake Analytics account for which to list Azure Storage accounts.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="51836-153">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="51836-153">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="51836-154">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="51836-154">OData Select statement.</span></span> <span data-ttu-id="51836-155">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="51836-155">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="51836-156">省略可能。</span><span class="sxs-lookup"><span data-stu-id="51836-156">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="51836-157">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="51836-157">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="51836-158">省略可能。</span><span class="sxs-lookup"><span data-stu-id="51836-158">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-159">指定された Data Lake Analytics アカウントに、リンクされている場合は、Azure ストレージ アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-159">Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="51836-160">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="51836-160">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListByAccountAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-162">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-162">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-163">名前、Data Lake Analytics アカウントを Azure ストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="51836-163">The name of the Data Lake Analytics account for which to list Azure Storage accounts.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="51836-164">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="51836-164">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="51836-165">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="51836-165">OData Select statement.</span></span> <span data-ttu-id="51836-166">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="51836-166">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="51836-167">省略可能。</span><span class="sxs-lookup"><span data-stu-id="51836-167">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="51836-168">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="51836-168">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="51836-169">省略可能。</span><span class="sxs-lookup"><span data-stu-id="51836-169">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-171">指定された Data Lake Analytics アカウントに、リンクされている場合は、Azure ストレージ アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-171">Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="51836-172">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="51836-172">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IStorageAccountsOperations, nextPageLink As String) As IPage(Of StorageAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-173">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="51836-174">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="51836-174">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-175">指定された Data Lake Analytics アカウントに、リンクされている場合は、Azure ストレージ アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-175">Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="51836-176">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="51836-176">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-177">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="51836-178">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="51836-178">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-180">指定された Data Lake Analytics アカウントに、リンクされている場合は、Azure ストレージ アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-180">Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="51836-181">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="51836-181">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokens">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokens (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokens(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokens(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSasTokens (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, containerName As String) As IPage(Of SasTokenInfo)" />
      <MemberSignature Language="F#" Value="static member ListSasTokens : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokens (operations, resourceGroupName, accountName, storageAccountName, containerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-183">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-183">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-184">Azure ストレージ アカウントの SAS トークンの要求された Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-184">The name of the Data Lake Analytics account from which an Azure Storage account's SAS token is being requested.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-185">SAS トークンを要求する Azure のストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-185">The name of the Azure storage account for which the SAS token is being requested.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="51836-186">SAS トークンを要求する対象の Azure ストレージ コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-186">The name of the Azure storage container for which the SAS token is being requested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-187">組み合わせに関連付けられた、指定された Data Lake Analytics と Azure ストレージ アカウントとコンテナーの SAS トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-187">Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSasTokensAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensAsync (operations, resourceGroupName, accountName, storageAccountName, containerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListSasTokensAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-189">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-189">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-190">Azure ストレージ アカウントの SAS トークンの要求された Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-190">The name of the Data Lake Analytics account from which an Azure Storage account's SAS token is being requested.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-191">SAS トークンを要求する Azure のストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-191">The name of the Azure storage account for which the SAS token is being requested.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="51836-192">SAS トークンを要求する対象の Azure ストレージ コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-192">The name of the Azure storage container for which the SAS token is being requested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-194">組み合わせに関連付けられた、指定された Data Lake Analytics と Azure ストレージ アカウントとコンテナーの SAS トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-194">Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokensNext (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokensNext(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNext(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSasTokensNext (operations As IStorageAccountsOperations, nextPageLink As String) As IPage(Of SasTokenInfo)" />
      <MemberSignature Language="F#" Value="static member ListSasTokensNext : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-195">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="51836-196">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="51836-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-197">組み合わせに関連付けられた、指定された Data Lake Analytics と Azure ストレージ アカウントとコンテナーの SAS トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-197">Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSasTokensNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListSasTokensNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-198">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="51836-199">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="51836-199">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-201">組み合わせに関連付けられた、指定された Data Lake Analytics と Azure ストレージ アカウントとコンテナーの SAS トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="51836-201">Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainers">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainers (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainers(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainers(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListStorageContainers (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String) As IPage(Of StorageContainer)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainers : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainers (operations, resourceGroupName, accountName, storageAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-202">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-202">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-203">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-203">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-204">名前 Data Lake Analytics アカウントを Azure Storage blob コンテナーの一覧にします。</span><span class="sxs-lookup"><span data-stu-id="51836-204">The name of the Data Lake Analytics account for which to list Azure Storage blob containers.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-205">Blob コンテナーの一覧を表示する Azure のストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-205">The name of the Azure storage account from which to list blob containers.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-206">指定された Data Lake Analytics と Azure ストレージ アカウントの組み合わせに関連付けられている場合は、Azure ストレージ コンテナーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="51836-206">Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination.</span></span> <span data-ttu-id="51836-207">応答には、存在する場合、結果の次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="51836-207">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainersAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersAsync (operations, resourceGroupName, accountName, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListStorageContainersAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-209">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-209">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-210">名前 Data Lake Analytics アカウントを Azure Storage blob コンテナーの一覧にします。</span><span class="sxs-lookup"><span data-stu-id="51836-210">The name of the Data Lake Analytics account for which to list Azure Storage blob containers.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-211">Blob コンテナーの一覧を表示する Azure のストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-211">The name of the Azure storage account from which to list blob containers.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-213">指定された Data Lake Analytics と Azure ストレージ アカウントの組み合わせに関連付けられている場合は、Azure ストレージ コンテナーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="51836-213">Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination.</span></span> <span data-ttu-id="51836-214">応答には、存在する場合、結果の次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="51836-214">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainersNext (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainersNext(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNext(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListStorageContainersNext (operations As IStorageAccountsOperations, nextPageLink As String) As IPage(Of StorageContainer)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainersNext : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-215">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="51836-216">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="51836-216">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-217">指定された Data Lake Analytics と Azure ストレージ アカウントの組み合わせに関連付けられている場合は、Azure ストレージ コンテナーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="51836-217">Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination.</span></span> <span data-ttu-id="51836-218">応答には、存在する場合、結果の次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="51836-218">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainersNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListStorageContainersNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-219">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-219">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="51836-220">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="51836-220">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-222">指定された Data Lake Analytics と Azure ストレージ アカウントの組み合わせに関連付けられている場合は、Azure ストレージ コンテナーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="51836-222">Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination.</span></span> <span data-ttu-id="51836-223">応答には、存在する場合、結果の次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="51836-223">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static void Update (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Update(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Update (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, Optional parameters As UpdateStorageAccountParameters = null)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Update (operations, resourceGroupName, accountName, storageAccountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-224">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-224">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-225">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-225">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-226">内のストレージ アカウントを変更する Data Lake Analytics アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="51836-226">The name of the Data Lake Analytics account to modify storage accounts in</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-227">Azure ストレージ アカウントを変更するには</span><span class="sxs-lookup"><span data-stu-id="51836-227">The Azure Storage account to modify</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51836-228">存在する場合に、アクセス キーと、ストレージ アカウントを更新するサフィックスを含むパラメーター。</span><span class="sxs-lookup"><span data-stu-id="51836-228">The parameters containing the access key and suffix to update the storage account with, if any.</span></span> <span data-ttu-id="51836-229">何も渡すことは、変更なしになります。</span><span class="sxs-lookup"><span data-stu-id="51836-229">Passing nothing results in no change.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-230">アクセス キーまたはサフィックスなど、Azure ストレージ blob アカウントの詳細を交換できる Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="51836-230">Updates the Data Lake Analytics account to replace Azure Storage blob account details, such as the access key and/or suffix.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, storageAccountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51836-231">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="51836-231">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51836-232">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="51836-232">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="51836-233">内のストレージ アカウントを変更する Data Lake Analytics アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="51836-233">The name of the Data Lake Analytics account to modify storage accounts in</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="51836-234">Azure ストレージ アカウントを変更するには</span><span class="sxs-lookup"><span data-stu-id="51836-234">The Azure Storage account to modify</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51836-235">存在する場合に、アクセス キーと、ストレージ アカウントを更新するサフィックスを含むパラメーター。</span><span class="sxs-lookup"><span data-stu-id="51836-235">The parameters containing the access key and suffix to update the storage account with, if any.</span></span> <span data-ttu-id="51836-236">何も渡すことは、変更なしになります。</span><span class="sxs-lookup"><span data-stu-id="51836-236">Passing nothing results in no change.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51836-237">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51836-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51836-238">アクセス キーまたはサフィックスなど、Azure ストレージ blob アカウントの詳細を交換できる Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="51836-238">Updates the Data Lake Analytics account to replace Azure Storage blob account details, such as the access key and/or suffix.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>