<Type Name="StorageAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="235a0-101">StorageAccountsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="235a0-101">Extension methods for StorageAccountsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;BeginCreateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="235a0-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="235a0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="235a0-103">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-103">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="235a0-104">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-104">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="235a0-105">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="235a0-105">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="235a0-106">作成したアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="235a0-106">The parameters to provide for the created account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="235a0-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="235a0-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="235a0-108">指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="235a0-108">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="235a0-109">アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。</span><span class="sxs-lookup"><span data-stu-id="235a0-109">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="235a0-110">アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。</span><span class="sxs-lookup"><span data-stu-id="235a0-110">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CheckNameAvailabilityAsync (operations, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="235a0-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="235a0-111">The operations group for this extension method.</span></span>
            </param>
        <param name="name"></param>
        <param name="cancellationToken">
            <span data-ttu-id="235a0-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="235a0-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="235a0-113">ストレージ アカウント名が有効で既に使用されていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="235a0-113">Checks that the storage account name is valid and is not already in use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; CreateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; CreateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="235a0-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="235a0-114">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="235a0-115">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-115">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="235a0-116">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-116">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="235a0-117">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="235a0-117">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="235a0-118">作成したアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="235a0-118">The parameters to provide for the created account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="235a0-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="235a0-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="235a0-120">指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="235a0-120">Asynchronously creates a new storage account with the specified parameters.</span></span>
            <span data-ttu-id="235a0-121">アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。</span><span class="sxs-lookup"><span data-stu-id="235a0-121">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="235a0-122">アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。</span><span class="sxs-lookup"><span data-stu-id="235a0-122">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="235a0-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="235a0-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="235a0-124">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-124">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="235a0-125">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-125">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="235a0-126">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="235a0-126">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="235a0-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="235a0-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="235a0-128">Microsoft Azure でストレージ アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="235a0-128">Deletes a storage account in Microsoft Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; GetPropertiesAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; GetPropertiesAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.GetPropertiesAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPropertiesAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.GetPropertiesAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;GetPropertiesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="235a0-129">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="235a0-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="235a0-130">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-130">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="235a0-131">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-131">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="235a0-132">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="235a0-132">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="235a0-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="235a0-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="235a0-134">指定されたストレージ アカウントなどは、name、SKU 名、場所、およびアカウントの状態のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="235a0-134">Returns the properties for the specified storage account including but not limited to name, SKU name, location, and account status.</span></span> <span data-ttu-id="235a0-135">ListKeys 操作は、記憶域のキーの取得を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="235a0-135">The ListKeys operation should be used to retrieve storage keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="235a0-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="235a0-136">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="235a0-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="235a0-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="235a0-138">サブスクリプションで使用可能なすべてのストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="235a0-138">Lists all the storage accounts available under the subscription.</span></span> <span data-ttu-id="235a0-139">ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="235a0-139">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="235a0-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="235a0-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="235a0-141">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-141">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="235a0-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="235a0-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="235a0-143">指定したリソース グループで使用可能なすべてのストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="235a0-143">Lists all the storage accounts available under the given resource group.</span></span>
            <span data-ttu-id="235a0-144">ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="235a0-144">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; ListKeysAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; ListKeysAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, accountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;ListKeysAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="235a0-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="235a0-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="235a0-146">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-146">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="235a0-147">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-147">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="235a0-148">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="235a0-148">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="235a0-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="235a0-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="235a0-150">指定されたストレージ アカウントのアクセス キーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="235a0-150">Lists the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, accountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;RegenerateKeyAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="235a0-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="235a0-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="235a0-152">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-152">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="235a0-153">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-153">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="235a0-154">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="235a0-154">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="keyName"></param>
        <param name="cancellationToken">
            <span data-ttu-id="235a0-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="235a0-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="235a0-156">指定されたストレージ アカウントのアクセス キーの 1 つを再生成します。</span><span class="sxs-lookup"><span data-stu-id="235a0-156">Regenerates one of the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; UpdateAsync (this Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt; UpdateAsync(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations,System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations * string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Storage.Fluent.StorageAccountsOperationsExtensions/&lt;UpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="235a0-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="235a0-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="235a0-158">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-158">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="235a0-159">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="235a0-159">The name of the storage account within the specified resource group.</span></span>
            <span data-ttu-id="235a0-160">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="235a0-160">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="235a0-161">更新されたアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="235a0-161">The parameters to provide for the updated account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="235a0-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="235a0-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="235a0-163">更新操作は、SKU、暗号化、アクセス層、またはストレージ アカウント用のタグの更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="235a0-163">The update operation can be used to update the SKU, encryption, access tier, or tags for a storage account.</span></span> <span data-ttu-id="235a0-164">カスタム ドメインにアカウントをマップにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="235a0-164">It can also be used to map the account to a custom domain.</span></span> <span data-ttu-id="235a0-165">ストレージ アカウントごとに 1 つのカスタム ドメインがサポートされます。カスタム ドメインの置換と変更はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="235a0-165">Only one custom domain is supported per storage account; the replacement/change of custom domain is not supported.</span></span> <span data-ttu-id="235a0-166">古いカスタム ドメインを置換するために古い値でなければなりませんクリア未登録の新しい値を設定する前に。</span><span class="sxs-lookup"><span data-stu-id="235a0-166">In order to replace an old custom domain, the old value must be cleared/unregistered before a new value can be set.</span></span> <span data-ttu-id="235a0-167">複数のプロパティの更新はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="235a0-167">The update of multiple properties is supported.</span></span> <span data-ttu-id="235a0-168">この呼び出しでは、ストレージ アカウントのキーは変更されません。</span><span class="sxs-lookup"><span data-stu-id="235a0-168">This call does not change the storage keys for the account.</span></span> <span data-ttu-id="235a0-169">ストレージ アカウント キーを変更する場合は、再生成のキー操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="235a0-169">If you want to change the storage account keys, use the regenerate keys operation.</span></span> <span data-ttu-id="235a0-170">作成後は、ストレージ アカウントの名前と場所を変更できません。</span><span class="sxs-lookup"><span data-stu-id="235a0-170">The location and name of the storage account cannot be changed after creation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>