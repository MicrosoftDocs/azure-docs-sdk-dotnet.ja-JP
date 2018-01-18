<Type Name="DataSliceOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataSliceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSliceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataSliceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataSliceOperationsExtensions = class" />
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDataSliceOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceListParameters) As DataSliceListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.List (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7f705-101">Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="7f705-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7f705-102">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-102">Required.</span></span> <span data-ttu-id="7f705-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="7f705-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="7f705-104">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-104">Required.</span></span> <span data-ttu-id="7f705-105">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="7f705-105">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="7f705-106">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-106">Required.</span></span> <span data-ttu-id="7f705-107">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="7f705-107">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7f705-108">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-108">Required.</span></span> <span data-ttu-id="7f705-109">データセットのデータ スライスを一覧表示する方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7f705-109">Parameters specifying how to list data slices of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7f705-110">次のページにリンクを使用してデータ スライスのインスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="7f705-110">Gets the first page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7f705-111">リストのデータは、操作の応答をスライスします。</span><span class="sxs-lookup"><span data-stu-id="7f705-111">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDataSliceOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceListParameters) As Task(Of DataSliceListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7f705-112">Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="7f705-112">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7f705-113">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-113">Required.</span></span> <span data-ttu-id="7f705-114">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="7f705-114">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="7f705-115">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-115">Required.</span></span> <span data-ttu-id="7f705-116">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="7f705-116">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="7f705-117">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-117">Required.</span></span> <span data-ttu-id="7f705-118">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="7f705-118">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7f705-119">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-119">Required.</span></span> <span data-ttu-id="7f705-120">データセットのデータ スライスを一覧表示する方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7f705-120">Parameters specifying how to list data slices of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7f705-121">次のページにリンクを使用してデータ スライスのインスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="7f705-121">Gets the first page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7f705-122">リストのデータは、操作の応答をスライスします。</span><span class="sxs-lookup"><span data-stu-id="7f705-122">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDataSliceOperations, nextLink As String) As DataSliceListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7f705-123">Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="7f705-123">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="7f705-124">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-124">Required.</span></span> <span data-ttu-id="7f705-125">次のデータ スライスのページの url です。</span><span class="sxs-lookup"><span data-stu-id="7f705-125">The url to the next data slices page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7f705-126">次のページにリンクを使用してデータ スライスのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="7f705-126">Gets the next page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7f705-127">リストのデータは、操作の応答をスライスします。</span><span class="sxs-lookup"><span data-stu-id="7f705-127">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDataSliceOperations, nextLink As String) As Task(Of DataSliceListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7f705-128">Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="7f705-128">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="7f705-129">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-129">Required.</span></span> <span data-ttu-id="7f705-130">次のデータ スライスのページの url です。</span><span class="sxs-lookup"><span data-stu-id="7f705-130">The url to the next data slices page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7f705-131">次のページにリンクを使用してデータ スライスのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="7f705-131">Gets the next page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7f705-132">リストのデータは、操作の応答をスライスします。</span><span class="sxs-lookup"><span data-stu-id="7f705-132">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse SetStatus (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse SetStatus(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.SetStatus(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetStatus (operations As IDataSliceOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceSetStatusParameters) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member SetStatus : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.SetStatus (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7f705-133">Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="7f705-133">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7f705-134">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-134">Required.</span></span> <span data-ttu-id="7f705-135">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="7f705-135">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="7f705-136">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-136">Required.</span></span> <span data-ttu-id="7f705-137">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="7f705-137">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="7f705-138">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-138">Required.</span></span> <span data-ttu-id="7f705-139">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="7f705-139">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7f705-140">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-140">Required.</span></span> <span data-ttu-id="7f705-141">データ スライスの状態を設定するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7f705-141">The parameters required to set status of data slices.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7f705-142">データセットの特定の時間範囲には、データ スライスの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f705-142">Sets status of data slices over a time range for a specific dataset.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7f705-143">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="7f705-143">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.SetStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetStatusAsync (operations As IDataSliceOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceSetStatusParameters) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member SetStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.SetStatusAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7f705-144">Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="7f705-144">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7f705-145">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-145">Required.</span></span> <span data-ttu-id="7f705-146">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="7f705-146">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="7f705-147">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-147">Required.</span></span> <span data-ttu-id="7f705-148">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="7f705-148">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="7f705-149">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-149">Required.</span></span> <span data-ttu-id="7f705-150">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="7f705-150">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7f705-151">必須。</span><span class="sxs-lookup"><span data-stu-id="7f705-151">Required.</span></span> <span data-ttu-id="7f705-152">データ スライスの状態を設定するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7f705-152">The parameters required to set status of data slices.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7f705-153">データセットの特定の時間範囲には、データ スライスの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f705-153">Sets status of data slices over a time range for a specific dataset.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7f705-154">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="7f705-154">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>