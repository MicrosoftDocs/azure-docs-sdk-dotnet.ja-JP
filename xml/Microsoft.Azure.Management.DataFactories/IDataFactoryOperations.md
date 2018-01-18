<Type Name="IDataFactoryOperations" FullName="Microsoft.Azure.Management.DataFactories.IDataFactoryOperations">
  <TypeSignature Language="C#" Value="public interface IDataFactoryOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataFactoryOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataFactoryOperations" />
  <TypeSignature Language="F#" Value="type IDataFactoryOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="33908-101">データ ファクトリを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="33908-101">Operations for managing data factories.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.BeginCreateOrUpdateAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="iDataFactoryOperations.BeginCreateOrUpdateAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="33908-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="33908-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="33908-103">作成または更新、データ ファクトリに必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="33908-103">The parameters required to create or update a data factory.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="33908-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="33908-104">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33908-105">作成またはデータ ファクトリを更新します。</span><span class="sxs-lookup"><span data-stu-id="33908-105">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33908-106">作成または更新データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="33908-106">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.CreateOrUpdateAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="iDataFactoryOperations.CreateOrUpdateAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="33908-107">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="33908-107">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="33908-108">作成または更新、データ ファクトリに必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="33908-108">The parameters required to create or update a data factory.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="33908-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="33908-109">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33908-110">作成またはデータ ファクトリを更新します。</span><span class="sxs-lookup"><span data-stu-id="33908-110">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33908-111">作成または更新データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="33908-111">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.DeleteAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDataFactoryOperations.DeleteAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="33908-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="33908-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="33908-113">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="33908-113">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="33908-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="33908-114">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33908-115">データ ファクトリのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="33908-115">Delete a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33908-116">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="33908-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.GetAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt;" Usage="iDataFactoryOperations.GetAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="33908-117">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="33908-117">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="33908-118">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="33908-118">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="33908-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="33908-119">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33908-120">データ ファクトリのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="33908-120">Gets a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33908-121">データ ファクトリを取得操作応答します。</span><span class="sxs-lookup"><span data-stu-id="33908-121">The Get data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="iDataFactoryOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="33908-122">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="33908-122">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="33908-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="33908-123">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33908-124">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="33908-124">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="33908-125">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="33908-125">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33908-126">作成または更新データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="33908-126">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListAsync (string resourceGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListAsync(string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.ListAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;" Usage="iDataFactoryOperations.ListAsync (resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="33908-127">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="33908-127">The resource group name of the data factories.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="33908-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="33908-128">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33908-129">次のページへのリンクがデータ ファクトリのインスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="33908-129">Gets the first page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33908-130">一覧データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="33908-130">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataFactoryOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;" Usage="iDataFactoryOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="33908-131">次のデータ ファクトリのページの url です。</span><span class="sxs-lookup"><span data-stu-id="33908-131">The url to the next data factories page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="33908-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="33908-132">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="33908-133">次のページへのリンクがデータ ファクトリのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="33908-133">Gets the next page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="33908-134">一覧データ ファクトリ操作応答です。</span><span class="sxs-lookup"><span data-stu-id="33908-134">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>