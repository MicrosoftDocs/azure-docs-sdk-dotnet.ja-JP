<Type Name="DatasetOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatasetOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatasetOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatasetOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatasetOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-101">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-101">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-102">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-102">Required.</span></span> <span data-ttu-id="b32fa-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-104">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-104">Required.</span></span> <span data-ttu-id="b32fa-105">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-105">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b32fa-106">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-106">Required.</span></span> <span data-ttu-id="b32fa-107">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b32fa-107">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-108">データセットの新しいインスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-108">Create a new Dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-109">CreateOrUpdate データセット操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-109">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-110">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-110">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-111">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-111">Required.</span></span> <span data-ttu-id="b32fa-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-113">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-113">Required.</span></span> <span data-ttu-id="b32fa-114">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-114">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b32fa-115">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-115">Required.</span></span> <span data-ttu-id="b32fa-116">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b32fa-116">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-117">データセットの新しいインスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-117">Create a new Dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-118">CreateOrUpdate データセット操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-118">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContent (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-119">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-119">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-120">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-120">Required.</span></span> <span data-ttu-id="b32fa-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-122">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-122">Required.</span></span> <span data-ttu-id="b32fa-123">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-123">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="b32fa-124">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-124">Required.</span></span> <span data-ttu-id="b32fa-125">データセットのインスタンスの一意名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-125">A unique Dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b32fa-126">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-126">Required.</span></span> <span data-ttu-id="b32fa-127">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b32fa-127">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-128">データセットの新しいインスタンスを作成または、生の JSON コンテンツを持つ既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-128">Create a new Dataset instance or update an existing instance with raw JSON content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-129">CreateOrUpdate データセット操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-129">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContentAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-130">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-130">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-131">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-131">Required.</span></span> <span data-ttu-id="b32fa-132">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-132">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-133">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-133">Required.</span></span> <span data-ttu-id="b32fa-134">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-134">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="b32fa-135">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-135">Required.</span></span> <span data-ttu-id="b32fa-136">データセットのインスタンスの一意名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-136">A unique Dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b32fa-137">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-137">Required.</span></span> <span data-ttu-id="b32fa-138">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b32fa-138">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-139">データセットの新しいインスタンスを作成または、生の JSON コンテンツを持つ既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-139">Create a new Dataset instance or update an existing instance with raw JSON content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-140">CreateOrUpdate データセット操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-140">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-141">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-141">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-142">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-142">Required.</span></span> <span data-ttu-id="b32fa-143">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-143">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-144">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-144">Required.</span></span> <span data-ttu-id="b32fa-145">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-145">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="b32fa-146">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-146">Required.</span></span> <span data-ttu-id="b32fa-147">データセットの名前です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-147">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-148">データセットのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-148">Delete a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-149">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-149">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-150">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-150">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-151">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-151">Required.</span></span> <span data-ttu-id="b32fa-152">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-152">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-153">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-153">Required.</span></span> <span data-ttu-id="b32fa-154">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-154">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="b32fa-155">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-155">Required.</span></span> <span data-ttu-id="b32fa-156">データセットの名前です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-156">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-157">データセットのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-157">Delete a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-158">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-158">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-159">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-159">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-160">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-160">Required.</span></span> <span data-ttu-id="b32fa-161">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-162">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-162">Required.</span></span> <span data-ttu-id="b32fa-163">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-163">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b32fa-164">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-164">Required.</span></span> <span data-ttu-id="b32fa-165">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b32fa-165">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-166">データセットの新しいインスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-166">Create a new Dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-167">CreateOrUpdate データセット操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-167">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-168">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-168">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-169">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-169">Required.</span></span> <span data-ttu-id="b32fa-170">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-171">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-171">Required.</span></span> <span data-ttu-id="b32fa-172">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-172">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b32fa-173">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-173">Required.</span></span> <span data-ttu-id="b32fa-174">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b32fa-174">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-175">データセットの新しいインスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-175">Create a new Dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-176">CreateOrUpdate データセット操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-176">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-177">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-177">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-178">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-178">Required.</span></span> <span data-ttu-id="b32fa-179">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-180">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-180">Required.</span></span> <span data-ttu-id="b32fa-181">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-181">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="b32fa-182">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-182">Required.</span></span> <span data-ttu-id="b32fa-183">データセットのインスタンスの一意名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-183">A unique Dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b32fa-184">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-184">Required.</span></span> <span data-ttu-id="b32fa-185">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b32fa-185">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-186">データセットの新しいインスタンスを作成または、生の json コンテンツを持つ既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-186">Create a new Dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-187">CreateOrUpdate データセット操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-187">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-188">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-188">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-189">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-189">Required.</span></span> <span data-ttu-id="b32fa-190">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-190">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-191">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-191">Required.</span></span> <span data-ttu-id="b32fa-192">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-192">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="b32fa-193">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-193">Required.</span></span> <span data-ttu-id="b32fa-194">データセットのインスタンスの一意名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-194">A unique Dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b32fa-195">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-195">Required.</span></span> <span data-ttu-id="b32fa-196">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b32fa-196">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-197">データセットの新しいインスタンスを作成または、生の json コンテンツを持つ既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-197">Create a new Dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-198">CreateOrUpdate データセット操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-198">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-199">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-199">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-200">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-200">Required.</span></span> <span data-ttu-id="b32fa-201">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-201">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-202">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-202">Required.</span></span> <span data-ttu-id="b32fa-203">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-203">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="b32fa-204">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-204">Required.</span></span> <span data-ttu-id="b32fa-205">データセットの名前です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-205">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-206">データセットのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-206">Delete a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-207">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-207">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-208">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-208">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-209">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-209">Required.</span></span> <span data-ttu-id="b32fa-210">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-210">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-211">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-211">Required.</span></span> <span data-ttu-id="b32fa-212">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-212">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="b32fa-213">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-213">Required.</span></span> <span data-ttu-id="b32fa-214">データセットの名前です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-214">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-215">データセットのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-215">Delete a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-216">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-216">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse Get (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse Get(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As DatasetGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-217">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-217">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-218">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-218">Required.</span></span> <span data-ttu-id="b32fa-219">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-219">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-220">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-220">Required.</span></span> <span data-ttu-id="b32fa-221">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-221">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="b32fa-222">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-222">Required.</span></span> <span data-ttu-id="b32fa-223">データセットの名前です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-223">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-224">データセットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-224">Gets a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-225">データセットの取得操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-225">The Get Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of DatasetGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-226">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-226">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-227">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-227">Required.</span></span> <span data-ttu-id="b32fa-228">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-228">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-229">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-229">Required.</span></span> <span data-ttu-id="b32fa-230">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-230">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="b32fa-231">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-231">Required.</span></span> <span data-ttu-id="b32fa-232">データセットの名前です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-232">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-233">データセットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-233">Gets a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-234">データセットの取得操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-234">The Get Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IDatasetOperations, operationStatusLink As String) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-235">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-235">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="b32fa-236">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-236">Required.</span></span> <span data-ttu-id="b32fa-237">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-237">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="b32fa-238">CreateOrUpdate データセット操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-238">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IDatasetOperations, operationStatusLink As String) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-239">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-239">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="b32fa-240">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-240">Required.</span></span> <span data-ttu-id="b32fa-241">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-241">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="b32fa-242">CreateOrUpdate データセット操作の応答。</span><span class="sxs-lookup"><span data-stu-id="b32fa-242">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse List (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse List(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String) As DatasetListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-243">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-243">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-244">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-244">Required.</span></span> <span data-ttu-id="b32fa-245">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-245">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-246">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-246">Required.</span></span> <span data-ttu-id="b32fa-247">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-247">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-248">次のページへのリンクが、データ ファクトリ内のすべてのデータセットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-248">Gets all the Dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-249">一覧のデータセットの操作応答です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-249">The List Datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of DatasetListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-250">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-250">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b32fa-251">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-251">Required.</span></span> <span data-ttu-id="b32fa-252">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="b32fa-252">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="b32fa-253">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-253">Required.</span></span> <span data-ttu-id="b32fa-254">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-254">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-255">次のページへのリンクが、データ ファクトリ内のすべてのデータセットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-255">Gets all the Dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-256">一覧のデータセットの操作応答です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-256">The List Datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse ListNext (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse ListNext(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDatasetOperations, nextLink As String) As DatasetListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-257">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-257">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="b32fa-258">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-258">Required.</span></span> <span data-ttu-id="b32fa-259">[次へ] の [データセット] ページの url です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-259">The url to the next Datasets page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-260">次のページへのリンクを持つデータセットのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-260">Gets the next page of Dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-261">一覧のデータセットの操作応答です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-261">The List Datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDatasetOperations, nextLink As String) As Task(Of DatasetListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b32fa-262">Microsoft.Azure.Management.DataFactories.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b32fa-262">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="b32fa-263">必須。</span><span class="sxs-lookup"><span data-stu-id="b32fa-263">Required.</span></span> <span data-ttu-id="b32fa-264">[次へ] の [データセット] ページの url です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-264">The url to the next Datasets page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b32fa-265">次のページへのリンクを持つデータセットのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="b32fa-265">Gets the next page of Dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b32fa-266">一覧のデータセットの操作応答です。</span><span class="sxs-lookup"><span data-stu-id="b32fa-266">The List Datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>