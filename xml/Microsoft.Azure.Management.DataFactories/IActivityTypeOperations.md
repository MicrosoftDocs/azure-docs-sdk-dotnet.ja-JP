<Type Name="IActivityTypeOperations" FullName="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations">
  <TypeSignature Language="C#" Value="public interface IActivityTypeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActivityTypeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActivityTypeOperations" />
  <TypeSignature Language="F#" Value="type IActivityTypeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7d985-101">データ ファクトリ Activitytype を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="7d985-101">Operations for managing data factory ActivityTypes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iActivityTypeOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, activityTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d985-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="7d985-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="7d985-103">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="7d985-103">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="7d985-104">ActivityType の名前。</span><span class="sxs-lookup"><span data-stu-id="7d985-104">The name of the activityType.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d985-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d985-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d985-106">ActivityType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="7d985-106">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7d985-107">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="7d985-107">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="iActivityTypeOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d985-108">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="7d985-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="7d985-109">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="7d985-109">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d985-110">作成または ActivityType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7d985-110">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d985-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d985-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d985-112">作成または、ActivityType を更新します。</span><span class="sxs-lookup"><span data-stu-id="7d985-112">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7d985-113">作成または更新 ActivityType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="7d985-113">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="iActivityTypeOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, activityTypeName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d985-114">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="7d985-114">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="7d985-115">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="7d985-115">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="7d985-116">ActivityType の名。</span><span class="sxs-lookup"><span data-stu-id="7d985-116">An ActivityType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d985-117">作成または ActivityType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7d985-117">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d985-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d985-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d985-119">作成または、ActivityType を更新します。</span><span class="sxs-lookup"><span data-stu-id="7d985-119">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7d985-120">作成または更新 ActivityType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="7d985-120">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iActivityTypeOperations.DeleteAsync (resourceGroupName, dataFactoryName, activityTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d985-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="7d985-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="7d985-122">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="7d985-122">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="7d985-123">ActivityType の名前。</span><span class="sxs-lookup"><span data-stu-id="7d985-123">The name of the activityType.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d985-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d985-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d985-125">ActivityType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="7d985-125">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7d985-126">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="7d985-126">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;" Usage="iActivityTypeOperations.GetAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d985-127">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="7d985-127">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="7d985-128">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="7d985-128">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d985-129">ActivityType 定義を取得する方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7d985-129">Parameters specifying how to get an ActivityType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d985-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d985-130">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d985-131">ActivityType インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="7d985-131">Gets an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7d985-132">ActivityType の取得操作の応答。</span><span class="sxs-lookup"><span data-stu-id="7d985-132">The Get ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="iActivityTypeOperations.ListAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7d985-133">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="7d985-133">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="7d985-134">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="7d985-134">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7d985-135">ActivityType 定義の一覧を返す方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7d985-135">Parameters specifying how to return a list of ActivityType definitions.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d985-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d985-136">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d985-137">次のページへのリンクを持つ ActivityType インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="7d985-137">Gets the first page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7d985-138">リスト ActivityType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="7d985-138">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="iActivityTypeOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="7d985-139">[次へ] の [Activitytype] ページの url です。</span><span class="sxs-lookup"><span data-stu-id="7d985-139">The url to the next ActivityTypes page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7d985-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7d985-140">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7d985-141">次のページへのリンクを持つ ActivityType インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="7d985-141">Gets the next page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7d985-142">リスト ActivityType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="7d985-142">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>