<Type Name="DataSliceRunOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataSliceRunOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSliceRunOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataSliceRunOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataSliceRunOperationsExtensions = class" />
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string runId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string runId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, runId As String) As DataSliceRunGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, runId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="16d88-101">Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="16d88-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="16d88-102">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-102">Required.</span></span> <span data-ttu-id="16d88-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="16d88-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="16d88-104">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-104">Required.</span></span> <span data-ttu-id="16d88-105">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="16d88-105">A unique data factory instance name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="16d88-106">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-106">Required.</span></span> <span data-ttu-id="16d88-107">一意のデータ スライスの実行の id。</span><span class="sxs-lookup"><span data-stu-id="16d88-107">A unique Data Slice Run Id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="16d88-108">データ スライスの実行のインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="16d88-108">Gets a Data Slice Run instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="16d88-109">Get 操作の応答のデータ スライスを実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-109">The get Data Slice Run operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string runId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string runId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, runId As String) As Task(Of DataSliceRunGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, runId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="16d88-110">Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="16d88-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="16d88-111">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-111">Required.</span></span> <span data-ttu-id="16d88-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="16d88-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="16d88-113">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-113">Required.</span></span> <span data-ttu-id="16d88-114">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="16d88-114">A unique data factory instance name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="16d88-115">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-115">Required.</span></span> <span data-ttu-id="16d88-116">一意のデータ スライスの実行の id。</span><span class="sxs-lookup"><span data-stu-id="16d88-116">A unique Data Slice Run Id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="16d88-117">データ スライスの実行のインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="16d88-117">Gets a Data Slice Run instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="16d88-118">Get 操作の応答のデータ スライスを実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-118">The get Data Slice Run operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogs">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse GetLogs (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string dataSliceRunId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse GetLogs(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string dataSliceRunId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetLogs(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLogs (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, dataSliceRunId As String) As DataSliceRunGetLogsResponse" />
      <MemberSignature Language="F#" Value="static member GetLogs : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetLogs (operations, resourceGroupName, dataFactoryName, dataSliceRunId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataSliceRunId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="16d88-119">Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="16d88-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="16d88-120">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-120">Required.</span></span> <span data-ttu-id="16d88-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="16d88-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="16d88-122">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-122">Required.</span></span> <span data-ttu-id="16d88-123">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="16d88-123">A unique data factory instance name.</span></span>
            </param>
        <param name="dataSliceRunId">
            <span data-ttu-id="16d88-124">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-124">Required.</span></span> <span data-ttu-id="16d88-125">一意のデータ スライスは、インスタンス id を実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-125">A unique data slice run instance id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="16d88-126">データ スライスの実行のログを取得します。</span><span class="sxs-lookup"><span data-stu-id="16d88-126">Gets logs for a data slice run</span></span>
            </summary>
        <returns>
            <span data-ttu-id="16d88-127">データ スライスは、get ログ操作の応答を実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-127">The data slice run get logs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string dataSliceRunId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string dataSliceRunId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetLogsAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLogsAsync (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, dataSliceRunId As String) As Task(Of DataSliceRunGetLogsResponse)" />
      <MemberSignature Language="F#" Value="static member GetLogsAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetLogsAsync (operations, resourceGroupName, dataFactoryName, dataSliceRunId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataSliceRunId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="16d88-128">Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="16d88-128">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="16d88-129">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-129">Required.</span></span> <span data-ttu-id="16d88-130">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="16d88-130">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="16d88-131">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-131">Required.</span></span> <span data-ttu-id="16d88-132">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="16d88-132">A unique data factory instance name.</span></span>
            </param>
        <param name="dataSliceRunId">
            <span data-ttu-id="16d88-133">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-133">Required.</span></span> <span data-ttu-id="16d88-134">一意のデータ スライスは、インスタンス id を実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-134">A unique data slice run instance id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="16d88-135">データ スライスの実行のログを取得します。</span><span class="sxs-lookup"><span data-stu-id="16d88-135">Gets logs for a data slice run</span></span>
            </summary>
        <returns>
            <span data-ttu-id="16d88-136">データ スライスは、get ログ操作の応答を実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-136">The data slice run get logs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceRunListParameters) As DataSliceRunListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.List (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="16d88-137">Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="16d88-137">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="16d88-138">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-138">Required.</span></span> <span data-ttu-id="16d88-139">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="16d88-139">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="16d88-140">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-140">Required.</span></span> <span data-ttu-id="16d88-141">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="16d88-141">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="16d88-142">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-142">Required.</span></span> <span data-ttu-id="16d88-143">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="16d88-143">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="16d88-144">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-144">Required.</span></span> <span data-ttu-id="16d88-145">データセットのデータ スライスの一覧にフィルターを指定するためのパラメーターが実行されます。</span><span class="sxs-lookup"><span data-stu-id="16d88-145">Parameters for specifying the filters to list data slice runs of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="16d88-146">次のページにリンクを使用してインスタンスを実行するデータ スライスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="16d88-146">Gets the first page of data slice run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="16d88-147">一覧のデータ スライスは、操作の応答を実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-147">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceRunListParameters) As Task(Of DataSliceRunListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="16d88-148">Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="16d88-148">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="16d88-149">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-149">Required.</span></span> <span data-ttu-id="16d88-150">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="16d88-150">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="16d88-151">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-151">Required.</span></span> <span data-ttu-id="16d88-152">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="16d88-152">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="16d88-153">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-153">Required.</span></span> <span data-ttu-id="16d88-154">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="16d88-154">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="16d88-155">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-155">Required.</span></span> <span data-ttu-id="16d88-156">データセットのデータ スライスの一覧にフィルターを指定するためのパラメーターが実行されます。</span><span class="sxs-lookup"><span data-stu-id="16d88-156">Parameters for specifying the filters to list data slice runs of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="16d88-157">次のページにリンクを使用してインスタンスを実行するデータ スライスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="16d88-157">Gets the first page of data slice run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="16d88-158">一覧のデータ スライスは、操作の応答を実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-158">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDataSliceRunOperations, nextLink As String) As DataSliceRunListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="16d88-159">Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="16d88-159">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="16d88-160">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-160">Required.</span></span> <span data-ttu-id="16d88-161">次のデータ スライスへの url は、ページを実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-161">The url to the next data slice runs page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="16d88-162">次のページへのリンクを持つ実行のインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="16d88-162">Gets the next page of run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="16d88-163">一覧のデータ スライスは、操作の応答を実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-163">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDataSliceRunOperations, nextLink As String) As Task(Of DataSliceRunListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="16d88-164">Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="16d88-164">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="16d88-165">必須。</span><span class="sxs-lookup"><span data-stu-id="16d88-165">Required.</span></span> <span data-ttu-id="16d88-166">次のデータ スライスへの url は、ページを実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-166">The url to the next data slice runs page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="16d88-167">次のページへのリンクを持つ実行のインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="16d88-167">Gets the next page of run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="16d88-168">一覧のデータ スライスは、操作の応答を実行します。</span><span class="sxs-lookup"><span data-stu-id="16d88-168">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>