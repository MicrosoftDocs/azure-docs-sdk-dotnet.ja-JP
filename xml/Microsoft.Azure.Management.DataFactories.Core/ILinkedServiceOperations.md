<Type Name="ILinkedServiceOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations">
  <TypeSignature Language="C#" Value="public interface ILinkedServiceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILinkedServiceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILinkedServiceOperations" />
  <TypeSignature Language="F#" Value="type ILinkedServiceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bee3b-101">データ ファクトリの内部 linkedServices を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-101">Operations for managing data factory internal linkedServices.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bee3b-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="bee3b-103">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="bee3b-103">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bee3b-104">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="bee3b-104">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bee3b-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bee3b-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bee3b-106">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-106">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bee3b-107">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-107">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.BeginCreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.BeginCreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, linkedServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bee3b-108">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="bee3b-109">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="bee3b-109">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="bee3b-110">作成または更新するデータ ファクトリのデータセットの名前。</span><span class="sxs-lookup"><span data-stu-id="bee3b-110">The name of the data factory dataset to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bee3b-111">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="bee3b-111">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bee3b-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bee3b-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bee3b-113">作成または、生の json コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-113">Create or update a data factory linkedService with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bee3b-114">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-114">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iLinkedServiceOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, linkedServiceName, cancellationToken)" />
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
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bee3b-115">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-115">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="bee3b-116">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-116">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="bee3b-117">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-117">A unique data factory linkedService name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bee3b-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bee3b-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bee3b-119">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-119">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bee3b-120">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-120">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bee3b-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="bee3b-122">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="bee3b-122">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bee3b-123">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="bee3b-123">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bee3b-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bee3b-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bee3b-125">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-125">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bee3b-126">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-126">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, linkedServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bee3b-127">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-127">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="bee3b-128">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="bee3b-128">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="bee3b-129">データ ファクトリの名前には、作成または更新するサービスがリンクされています。</span><span class="sxs-lookup"><span data-stu-id="bee3b-129">The name of the data factory linked service to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bee3b-130">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="bee3b-130">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bee3b-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bee3b-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bee3b-132">作成または、生の json コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-132">Create or update a data factory linkedService with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bee3b-133">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-133">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iLinkedServiceOperations.DeleteAsync (resourceGroupName, dataFactoryName, linkedServiceName, cancellationToken)" />
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
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bee3b-134">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-134">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="bee3b-135">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-135">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="bee3b-136">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-136">A unique data factory linkedService name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bee3b-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bee3b-137">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bee3b-138">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-138">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bee3b-139">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-139">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse&gt;" Usage="iLinkedServiceOperations.GetAsync (resourceGroupName, dataFactoryName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bee3b-140">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-140">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="bee3b-141">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-141">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="bee3b-142">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-142">A unique data factory linkedService name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bee3b-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bee3b-143">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bee3b-144">データ ファクトリの linkedService インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-144">Gets a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bee3b-145">Get データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-145">The Get data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="bee3b-146">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-146">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bee3b-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bee3b-147">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="bee3b-148">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-148">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt;" Usage="iLinkedServiceOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bee3b-149">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="bee3b-149">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="bee3b-150">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-150">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bee3b-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bee3b-151">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bee3b-152">次のページへのリンクにリンクされたサービス インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-152">Gets the first page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bee3b-153">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-153">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt;" Usage="iLinkedServiceOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="bee3b-154">次のリンクされたサービス ページの url です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-154">The url to the next linked services page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bee3b-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bee3b-155">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bee3b-156">次のページへのリンクにリンクされたサービス インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="bee3b-156">Gets the next page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bee3b-157">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="bee3b-157">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>