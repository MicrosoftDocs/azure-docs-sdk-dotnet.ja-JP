<Type Name="DatasetOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatasetOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatasetOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-101">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-102">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-102">Required.</span></span> <span data-ttu-id="4e647-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-104">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-104">Required.</span></span> <span data-ttu-id="4e647-105">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-105">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4e647-106">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-106">Required.</span></span> <span data-ttu-id="4e647-107">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4e647-107">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-108">データセットの新しいインスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="4e647-108">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-109">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-109">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-110">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-111">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-111">Required.</span></span> <span data-ttu-id="4e647-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-113">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-113">Required.</span></span> <span data-ttu-id="4e647-114">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-114">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4e647-115">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-115">Required.</span></span> <span data-ttu-id="4e647-116">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4e647-116">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-117">データセットの新しいインスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="4e647-117">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-118">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-118">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContent (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-119">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-120">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-120">Required.</span></span> <span data-ttu-id="4e647-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-122">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-122">Required.</span></span> <span data-ttu-id="4e647-123">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-123">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="4e647-124">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-124">Required.</span></span> <span data-ttu-id="4e647-125">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-125">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4e647-126">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-126">Required.</span></span> <span data-ttu-id="4e647-127">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4e647-127">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-128">データセットの新しいインスタンスを作成または、生の json コンテンツを持つ既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="4e647-128">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-129">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-129">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContentAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-130">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-130">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-131">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-131">Required.</span></span> <span data-ttu-id="4e647-132">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-132">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-133">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-133">Required.</span></span> <span data-ttu-id="4e647-134">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-134">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="4e647-135">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-135">Required.</span></span> <span data-ttu-id="4e647-136">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-136">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4e647-137">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-137">Required.</span></span> <span data-ttu-id="4e647-138">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4e647-138">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-139">データセットの新しいインスタンスを作成または、生の json コンテンツを持つ既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="4e647-139">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-140">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-140">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-141">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-141">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-142">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-142">Required.</span></span> <span data-ttu-id="4e647-143">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-143">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-144">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-144">Required.</span></span> <span data-ttu-id="4e647-145">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-145">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="4e647-146">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-146">Required.</span></span> <span data-ttu-id="4e647-147">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="4e647-147">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-148">データセットのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="4e647-148">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-149">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="4e647-149">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-150">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-150">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-151">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-151">Required.</span></span> <span data-ttu-id="4e647-152">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-152">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-153">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-153">Required.</span></span> <span data-ttu-id="4e647-154">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-154">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="4e647-155">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-155">Required.</span></span> <span data-ttu-id="4e647-156">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="4e647-156">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-157">データセットのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="4e647-157">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-158">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="4e647-158">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-159">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-159">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-160">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-160">Required.</span></span> <span data-ttu-id="4e647-161">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-162">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-162">Required.</span></span> <span data-ttu-id="4e647-163">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-163">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4e647-164">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-164">Required.</span></span> <span data-ttu-id="4e647-165">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4e647-165">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-166">データセットの新しいインスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="4e647-166">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-167">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-167">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-168">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-168">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-169">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-169">Required.</span></span> <span data-ttu-id="4e647-170">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-171">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-171">Required.</span></span> <span data-ttu-id="4e647-172">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-172">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4e647-173">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-173">Required.</span></span> <span data-ttu-id="4e647-174">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4e647-174">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-175">データセットの新しいインスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="4e647-175">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-176">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-176">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-177">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-177">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-178">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-178">Required.</span></span> <span data-ttu-id="4e647-179">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-180">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-180">Required.</span></span> <span data-ttu-id="4e647-181">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-181">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="4e647-182">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-182">Required.</span></span> <span data-ttu-id="4e647-183">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-183">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4e647-184">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-184">Required.</span></span> <span data-ttu-id="4e647-185">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4e647-185">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-186">データセットの新しいインスタンスを作成または、生の json コンテンツを持つ既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="4e647-186">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-187">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-187">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-188">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-188">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-189">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-189">Required.</span></span> <span data-ttu-id="4e647-190">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-190">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-191">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-191">Required.</span></span> <span data-ttu-id="4e647-192">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-192">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="4e647-193">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-193">Required.</span></span> <span data-ttu-id="4e647-194">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-194">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4e647-195">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-195">Required.</span></span> <span data-ttu-id="4e647-196">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4e647-196">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-197">データセットの新しいインスタンスを作成または、生の json コンテンツを持つ既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="4e647-197">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-198">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-198">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-199">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-199">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-200">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-200">Required.</span></span> <span data-ttu-id="4e647-201">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-201">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-202">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-202">Required.</span></span> <span data-ttu-id="4e647-203">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-203">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="4e647-204">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-204">Required.</span></span> <span data-ttu-id="4e647-205">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="4e647-205">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-206">データセットのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="4e647-206">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-207">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="4e647-207">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-208">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-208">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-209">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-209">Required.</span></span> <span data-ttu-id="4e647-210">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-210">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-211">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-211">Required.</span></span> <span data-ttu-id="4e647-212">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-212">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="4e647-213">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-213">Required.</span></span> <span data-ttu-id="4e647-214">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="4e647-214">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-215">データセットのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="4e647-215">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-216">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="4e647-216">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As DatasetGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-217">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-217">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-218">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-218">Required.</span></span> <span data-ttu-id="4e647-219">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-219">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-220">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-220">Required.</span></span> <span data-ttu-id="4e647-221">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-221">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="4e647-222">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-222">Required.</span></span> <span data-ttu-id="4e647-223">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="4e647-223">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-224">データセットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="4e647-224">Gets a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-225">Get データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-225">The Get dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of DatasetGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-226">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-226">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-227">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-227">Required.</span></span> <span data-ttu-id="4e647-228">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-228">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-229">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-229">Required.</span></span> <span data-ttu-id="4e647-230">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-230">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="4e647-231">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-231">Required.</span></span> <span data-ttu-id="4e647-232">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="4e647-232">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-233">データセットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="4e647-233">Gets a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-234">Get データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-234">The Get dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IDatasetOperations, operationStatusLink As String) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-235">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-235">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="4e647-236">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-236">Required.</span></span> <span data-ttu-id="4e647-237">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="4e647-237">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4e647-238">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-238">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IDatasetOperations, operationStatusLink As String) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-239">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-239">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="4e647-240">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-240">Required.</span></span> <span data-ttu-id="4e647-241">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="4e647-241">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4e647-242">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-242">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String) As DatasetListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-243">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-243">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-244">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-244">Required.</span></span> <span data-ttu-id="4e647-245">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-245">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-246">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-246">Required.</span></span> <span data-ttu-id="4e647-247">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-247">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-248">次のページへのリンクが、データ ファクトリ内のすべてのデータセットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="4e647-248">Gets all the dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-249">リストのデータセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-249">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of DatasetListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-250">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-250">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4e647-251">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-251">Required.</span></span> <span data-ttu-id="4e647-252">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4e647-252">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4e647-253">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-253">Required.</span></span> <span data-ttu-id="4e647-254">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4e647-254">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-255">次のページへのリンクが、データ ファクトリ内のすべてのデータセットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="4e647-255">Gets all the dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-256">リストのデータセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-256">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDatasetOperations, nextLink As String) As DatasetListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-257">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-257">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="4e647-258">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-258">Required.</span></span> <span data-ttu-id="4e647-259">[次へ] の [データセット] ページの url です。</span><span class="sxs-lookup"><span data-stu-id="4e647-259">The url to the next datasets page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-260">次のページへのリンクを持つデータセットのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="4e647-260">Gets the next page of dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-261">リストのデータセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-261">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDatasetOperations, nextLink As String) As Task(Of DatasetListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4e647-262">Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4e647-262">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="4e647-263">必須。</span><span class="sxs-lookup"><span data-stu-id="4e647-263">Required.</span></span> <span data-ttu-id="4e647-264">[次へ] の [データセット] ページの url です。</span><span class="sxs-lookup"><span data-stu-id="4e647-264">The url to the next datasets page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4e647-265">次のページへのリンクを持つデータセットのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="4e647-265">Gets the next page of dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4e647-266">リストのデータセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4e647-266">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>