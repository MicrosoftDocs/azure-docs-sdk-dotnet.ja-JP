<Type Name="ILinkedServiceOperations" FullName="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations">
  <TypeSignature Language="C#" Value="public interface ILinkedServiceOperations : Microsoft.Azure.Management.DataFactories.Conversion.ITypeRegistrationOperations&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILinkedServiceOperations implements class Microsoft.Azure.Management.DataFactories.Conversion.ITypeRegistrationOperations`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILinkedServiceOperations&#xA;Implements ITypeRegistrationOperations(Of LinkedService)" />
  <TypeSignature Language="F#" Value="type ILinkedServiceOperations = interface&#xA;    interface ITypeRegistrationOperations&lt;LinkedService&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataFactories.Conversion.ITypeRegistrationOperations&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedService&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="dfe03-101">データ ファクトリ linkedServices を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-101">Operations for managing data factory linkedServices.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="dfe03-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="dfe03-103">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="dfe03-103">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dfe03-104">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="dfe03-104">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dfe03-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dfe03-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dfe03-106">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-106">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dfe03-107">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-107">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.BeginCreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.BeginCreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, linkedServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="dfe03-108">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="dfe03-109">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="dfe03-109">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="dfe03-110">データ ファクトリの作成または更新するリンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="dfe03-110">The name of the data factory Linked Service to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dfe03-111">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="dfe03-111">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dfe03-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dfe03-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dfe03-113">作成または、生の JSON コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-113">Create or update a data factory linkedService with raw JSON content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dfe03-114">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-114">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="dfe03-115">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-115">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="dfe03-116">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-116">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="dfe03-117">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-117">A unique data factory linkedService name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dfe03-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dfe03-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dfe03-119">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-119">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dfe03-120">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-120">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="dfe03-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="dfe03-122">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="dfe03-122">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dfe03-123">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="dfe03-123">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dfe03-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dfe03-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dfe03-125">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-125">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dfe03-126">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-126">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, linkedServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="dfe03-127">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-127">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="dfe03-128">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="dfe03-128">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="dfe03-129">データ ファクトリの作成または更新するリンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="dfe03-129">The name of the data factory Linked Service to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dfe03-130">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="dfe03-130">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dfe03-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dfe03-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dfe03-132">作成または、生の JSON コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-132">Create or update a data factory linkedService with raw JSON content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dfe03-133">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-133">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="dfe03-134">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-134">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="dfe03-135">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-135">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="dfe03-136">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-136">A unique data factory linkedService name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dfe03-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dfe03-137">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dfe03-138">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-138">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dfe03-139">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-139">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string linkedServiceName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string linkedServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt;" Usage="iLinkedServiceOperations.GetAsync (resourceGroupName, dataFactoryName, linkedServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="dfe03-140">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-140">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="dfe03-141">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-141">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="dfe03-142">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-142">A unique data factory linkedService name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dfe03-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dfe03-143">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dfe03-144">データ ファクトリの linkedService インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-144">Gets a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dfe03-145">Get データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-145">The Get data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="iLinkedServiceOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="dfe03-146">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-146">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dfe03-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dfe03-147">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dfe03-148">リンクされたサービスの状態を作成または更新操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-148">Gets the status of a linked service create or update operation.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dfe03-149">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-149">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;" Usage="iLinkedServiceOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="dfe03-150">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="dfe03-150">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="dfe03-151">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-151">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dfe03-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dfe03-152">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dfe03-153">次のページへのリンクにリンクされたサービス インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-153">Gets the first page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dfe03-154">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-154">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;" Usage="iLinkedServiceOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="dfe03-155">次のリンクされたサービス ページの url です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-155">The url to the next linked services page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dfe03-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dfe03-156">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dfe03-157">次のページへのリンクにリンクされたサービス インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="dfe03-157">Gets the next page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dfe03-158">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="dfe03-158">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>