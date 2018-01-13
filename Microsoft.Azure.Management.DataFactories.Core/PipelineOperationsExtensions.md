<Type Name="PipelineOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PipelineOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PipelineOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PipelineOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PipelineOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, parameters As PipelineCreateOrUpdateParameters) As PipelineCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-101">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-102">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-102">Required.</span></span> <span data-ttu-id="775c8-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-104">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-104">Required.</span></span> <span data-ttu-id="775c8-105">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-105">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="775c8-106">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-106">Required.</span></span> <span data-ttu-id="775c8-107">作成またはパイプラインを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="775c8-107">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-108">作成またはパイプライン インスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="775c8-108">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-109">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-109">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, parameters As PipelineCreateOrUpdateParameters) As Task(Of PipelineCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-110">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-111">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-111">Required.</span></span> <span data-ttu-id="775c8-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-113">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-113">Required.</span></span> <span data-ttu-id="775c8-114">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-114">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="775c8-115">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-115">Required.</span></span> <span data-ttu-id="775c8-116">作成またはパイプラインを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="775c8-116">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-117">作成またはパイプライン インスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="775c8-117">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-118">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-118">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContent (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineCreateOrUpdateWithRawJsonContentParameters) As PipelineCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-119">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-120">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-120">Required.</span></span> <span data-ttu-id="775c8-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-122">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-122">Required.</span></span> <span data-ttu-id="775c8-123">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-123">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-124">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-124">Required.</span></span> <span data-ttu-id="775c8-125">パイプラインの一意のインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-125">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="775c8-126">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-126">Required.</span></span> <span data-ttu-id="775c8-127">パイプラインを作成するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="775c8-127">The parameters required to create a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-128">生の json コンテンツを持つ新しいパイプライン インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="775c8-128">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-129">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-129">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContentAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineCreateOrUpdateWithRawJsonContentParameters) As Task(Of PipelineCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-130">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-130">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-131">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-131">Required.</span></span> <span data-ttu-id="775c8-132">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-132">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-133">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-133">Required.</span></span> <span data-ttu-id="775c8-134">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-134">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-135">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-135">Required.</span></span> <span data-ttu-id="775c8-136">パイプラインの一意のインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-136">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="775c8-137">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-137">Required.</span></span> <span data-ttu-id="775c8-138">パイプラインを作成するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="775c8-138">The parameters required to create a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-139">生の json コンテンツを持つ新しいパイプライン インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="775c8-139">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-140">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-140">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-141">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-141">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-142">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-142">Required.</span></span> <span data-ttu-id="775c8-143">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-143">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-144">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-144">Required.</span></span> <span data-ttu-id="775c8-145">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-145">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-146">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-146">Required.</span></span> <span data-ttu-id="775c8-147">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-147">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-148">パイプラインのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="775c8-148">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-149">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="775c8-149">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-150">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-150">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-151">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-151">Required.</span></span> <span data-ttu-id="775c8-152">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-152">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-153">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-153">Required.</span></span> <span data-ttu-id="775c8-154">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-154">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-155">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-155">Required.</span></span> <span data-ttu-id="775c8-156">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-156">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-157">パイプラインのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="775c8-157">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-158">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="775c8-158">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, parameters As PipelineCreateOrUpdateParameters) As PipelineCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-159">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-159">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-160">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-160">Required.</span></span> <span data-ttu-id="775c8-161">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-162">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-162">Required.</span></span> <span data-ttu-id="775c8-163">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-163">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="775c8-164">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-164">Required.</span></span> <span data-ttu-id="775c8-165">作成またはパイプラインを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="775c8-165">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-166">作成またはパイプライン インスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="775c8-166">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-167">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-167">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, parameters As PipelineCreateOrUpdateParameters) As Task(Of PipelineCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-168">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-168">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-169">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-169">Required.</span></span> <span data-ttu-id="775c8-170">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-171">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-171">Required.</span></span> <span data-ttu-id="775c8-172">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-172">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="775c8-173">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-173">Required.</span></span> <span data-ttu-id="775c8-174">作成またはパイプラインを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="775c8-174">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-175">作成またはパイプライン インスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="775c8-175">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-176">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-176">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineCreateOrUpdateWithRawJsonContentParameters) As PipelineCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-177">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-177">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-178">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-178">Required.</span></span> <span data-ttu-id="775c8-179">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-180">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-180">Required.</span></span> <span data-ttu-id="775c8-181">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-181">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-182">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-182">Required.</span></span> <span data-ttu-id="775c8-183">パイプラインの一意のインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-183">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="775c8-184">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-184">Required.</span></span> <span data-ttu-id="775c8-185">作成またはパイプラインを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="775c8-185">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-186">生の json コンテンツを持つ新しいパイプライン インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="775c8-186">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-187">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-187">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineCreateOrUpdateWithRawJsonContentParameters) As Task(Of PipelineCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-188">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-188">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-189">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-189">Required.</span></span> <span data-ttu-id="775c8-190">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-190">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-191">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-191">Required.</span></span> <span data-ttu-id="775c8-192">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-192">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-193">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-193">Required.</span></span> <span data-ttu-id="775c8-194">パイプラインの一意のインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-194">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="775c8-195">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-195">Required.</span></span> <span data-ttu-id="775c8-196">作成またはパイプラインを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="775c8-196">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-197">生の json コンテンツを持つ新しいパイプライン インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="775c8-197">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-198">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-198">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-199">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-199">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-200">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-200">Required.</span></span> <span data-ttu-id="775c8-201">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-201">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-202">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-202">Required.</span></span> <span data-ttu-id="775c8-203">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-203">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-204">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-204">Required.</span></span> <span data-ttu-id="775c8-205">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-205">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-206">パイプラインのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="775c8-206">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-207">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="775c8-207">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-208">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-208">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-209">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-209">Required.</span></span> <span data-ttu-id="775c8-210">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-210">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-211">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-211">Required.</span></span> <span data-ttu-id="775c8-212">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-212">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-213">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-213">Required.</span></span> <span data-ttu-id="775c8-214">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-214">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-215">パイプラインのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="775c8-215">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-216">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="775c8-216">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As PipelineGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-217">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-217">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-218">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-218">Required.</span></span> <span data-ttu-id="775c8-219">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-219">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-220">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-220">Required.</span></span> <span data-ttu-id="775c8-221">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-221">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-222">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-222">Required.</span></span> <span data-ttu-id="775c8-223">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-223">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-224">パイプライン インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="775c8-224">Gets a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-225">Get パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-225">The Get pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As Task(Of PipelineGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-226">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-226">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-227">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-227">Required.</span></span> <span data-ttu-id="775c8-228">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-228">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-229">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-229">Required.</span></span> <span data-ttu-id="775c8-230">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-230">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-231">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-231">Required.</span></span> <span data-ttu-id="775c8-232">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-232">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-233">パイプライン インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="775c8-233">Gets a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-234">Get パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-234">The Get pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IPipelineOperations, operationStatusLink As String) As PipelineCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-235">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-235">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="775c8-236">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-236">Required.</span></span> <span data-ttu-id="775c8-237">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="775c8-237">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="775c8-238">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-238">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IPipelineOperations, operationStatusLink As String) As Task(Of PipelineCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-239">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-239">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="775c8-240">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-240">Required.</span></span> <span data-ttu-id="775c8-241">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="775c8-241">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="775c8-242">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="775c8-242">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String) As PipelineListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-243">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-243">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-244">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-244">Required.</span></span> <span data-ttu-id="775c8-245">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-245">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-246">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-246">Required.</span></span> <span data-ttu-id="775c8-247">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-247">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-248">次のページへのリンクを持つパイプライン インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="775c8-248">Gets the first page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-249">リストのパイプライン操作の応答。</span><span class="sxs-lookup"><span data-stu-id="775c8-249">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of PipelineListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-250">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-250">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-251">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-251">Required.</span></span> <span data-ttu-id="775c8-252">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-252">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-253">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-253">Required.</span></span> <span data-ttu-id="775c8-254">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-254">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-255">次のページへのリンクを持つパイプライン インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="775c8-255">Gets the first page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-256">リストのパイプライン操作の応答。</span><span class="sxs-lookup"><span data-stu-id="775c8-256">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPipelineOperations, nextLink As String) As PipelineListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-257">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-257">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="775c8-258">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-258">Required.</span></span> <span data-ttu-id="775c8-259">パイプラインの次のページの url です。</span><span class="sxs-lookup"><span data-stu-id="775c8-259">The url to the next pipelines page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-260">次のページへのリンクを持つパイプライン インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="775c8-260">Gets the next page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-261">リストのパイプライン操作の応答。</span><span class="sxs-lookup"><span data-stu-id="775c8-261">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IPipelineOperations, nextLink As String) As Task(Of PipelineListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-262">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-262">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="775c8-263">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-263">Required.</span></span> <span data-ttu-id="775c8-264">パイプラインの次のページの url です。</span><span class="sxs-lookup"><span data-stu-id="775c8-264">The url to the next pipelines page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-265">次のページへのリンクを持つパイプライン インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="775c8-265">Gets the next page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-266">リストのパイプライン操作の応答。</span><span class="sxs-lookup"><span data-stu-id="775c8-266">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resume">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Resume (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Resume(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Resume(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Resume (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Resume : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Resume (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-267">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-267">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-268">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-268">Required.</span></span> <span data-ttu-id="775c8-269">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-269">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-270">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-270">Required.</span></span> <span data-ttu-id="775c8-271">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-271">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-272">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-272">Required.</span></span> <span data-ttu-id="775c8-273">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-273">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-274">中断されたパイプラインが再開されます。</span><span class="sxs-lookup"><span data-stu-id="775c8-274">Resume a suspended pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-275">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="775c8-275">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ResumeAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ResumeAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-276">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-276">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-277">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-277">Required.</span></span> <span data-ttu-id="775c8-278">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-278">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-279">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-279">Required.</span></span> <span data-ttu-id="775c8-280">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-280">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-281">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-281">Required.</span></span> <span data-ttu-id="775c8-282">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-282">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-283">中断されたパイプラインが再開されます。</span><span class="sxs-lookup"><span data-stu-id="775c8-283">Resume a suspended pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-284">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="775c8-284">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetActivePeriod">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse SetActivePeriod (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse SetActivePeriod(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SetActivePeriod(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetActivePeriod (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineSetActivePeriodParameters) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member SetActivePeriod : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SetActivePeriod (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-285">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-285">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-286">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-286">Required.</span></span> <span data-ttu-id="775c8-287">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-287">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-288">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-288">Required.</span></span> <span data-ttu-id="775c8-289">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-289">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-290">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-290">Required.</span></span> <span data-ttu-id="775c8-291">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-291">Name of the data pipeline.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="775c8-292">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-292">Required.</span></span> <span data-ttu-id="775c8-293">パイプラインのアクティブな期間を設定するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="775c8-293">Parameters required to set the active period of a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-294">パイプラインのアクティブな期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="775c8-294">Sets the active period of a pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-295">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="775c8-295">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetActivePeriodAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetActivePeriodAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetActivePeriodAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SetActivePeriodAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetActivePeriodAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineSetActivePeriodParameters) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member SetActivePeriodAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SetActivePeriodAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-296">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-296">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-297">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-297">Required.</span></span> <span data-ttu-id="775c8-298">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-298">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-299">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-299">Required.</span></span> <span data-ttu-id="775c8-300">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-300">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-301">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-301">Required.</span></span> <span data-ttu-id="775c8-302">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-302">Name of the data pipeline.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="775c8-303">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-303">Required.</span></span> <span data-ttu-id="775c8-304">パイプラインのアクティブな期間を設定するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="775c8-304">Parameters required to set the active period of a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-305">パイプラインのアクティブな期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="775c8-305">Sets the active period of a pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-306">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="775c8-306">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspend">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Suspend (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Suspend(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Suspend(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Suspend (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Suspend : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Suspend (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-307">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-307">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-308">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-308">Required.</span></span> <span data-ttu-id="775c8-309">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-309">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-310">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-310">Required.</span></span> <span data-ttu-id="775c8-311">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-311">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-312">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-312">Required.</span></span> <span data-ttu-id="775c8-313">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-313">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-314">実行中のパイプラインを中断します。</span><span class="sxs-lookup"><span data-stu-id="775c8-314">Suspend a running pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-315">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="775c8-315">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SuspendAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SuspendAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member SuspendAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SuspendAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="775c8-316">Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="775c8-316">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="775c8-317">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-317">Required.</span></span> <span data-ttu-id="775c8-318">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="775c8-318">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="775c8-319">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-319">Required.</span></span> <span data-ttu-id="775c8-320">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="775c8-320">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="775c8-321">必須。</span><span class="sxs-lookup"><span data-stu-id="775c8-321">Required.</span></span> <span data-ttu-id="775c8-322">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="775c8-322">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="775c8-323">実行中のパイプラインを中断します。</span><span class="sxs-lookup"><span data-stu-id="775c8-323">Suspend a running pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="775c8-324">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="775c8-324">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>