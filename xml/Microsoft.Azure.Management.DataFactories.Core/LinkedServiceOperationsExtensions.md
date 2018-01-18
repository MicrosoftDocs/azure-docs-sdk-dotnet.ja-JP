<Type Name="LinkedServiceOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LinkedServiceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LinkedServiceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LinkedServiceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LinkedServiceOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, parameters As LinkedServiceCreateOrUpdateParameters) As LinkedServiceCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-101">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-102">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-102">Required.</span></span> <span data-ttu-id="ed0de-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-104">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-104">Required.</span></span> <span data-ttu-id="ed0de-105">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="ed0de-105">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ed0de-106">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-106">Required.</span></span> <span data-ttu-id="ed0de-107">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ed0de-107">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-108">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-108">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-109">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-109">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, parameters As LinkedServiceCreateOrUpdateParameters) As Task(Of LinkedServiceCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-110">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-111">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-111">Required.</span></span> <span data-ttu-id="ed0de-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-113">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-113">Required.</span></span> <span data-ttu-id="ed0de-114">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="ed0de-114">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ed0de-115">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-115">Required.</span></span> <span data-ttu-id="ed0de-116">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ed0de-116">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-117">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-117">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-118">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-118">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContent (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String, parameters As LinkedServiceCreateOrUpdateWithRawJsonContentParameters) As LinkedServiceCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, linkedServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-119">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-120">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-120">Required.</span></span> <span data-ttu-id="ed0de-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-122">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-122">Required.</span></span> <span data-ttu-id="ed0de-123">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="ed0de-123">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="ed0de-124">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-124">Required.</span></span> <span data-ttu-id="ed0de-125">作成または更新するデータ ファクトリのデータセットの名前。</span><span class="sxs-lookup"><span data-stu-id="ed0de-125">The name of the data factory dataset to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ed0de-126">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-126">Required.</span></span> <span data-ttu-id="ed0de-127">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ed0de-127">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-128">作成または、生の json コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-128">Create or update a data factory linkedService with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-129">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-129">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContentAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String, parameters As LinkedServiceCreateOrUpdateWithRawJsonContentParameters) As Task(Of LinkedServiceCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, linkedServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-130">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-130">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-131">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-131">Required.</span></span> <span data-ttu-id="ed0de-132">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-132">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-133">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-133">Required.</span></span> <span data-ttu-id="ed0de-134">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="ed0de-134">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="ed0de-135">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-135">Required.</span></span> <span data-ttu-id="ed0de-136">作成または更新するデータ ファクトリのデータセットの名前。</span><span class="sxs-lookup"><span data-stu-id="ed0de-136">The name of the data factory dataset to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ed0de-137">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-137">Required.</span></span> <span data-ttu-id="ed0de-138">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ed0de-138">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-139">作成または、生の json コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-139">Create or update a data factory linkedService with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-140">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-140">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-141">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-141">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-142">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-142">Required.</span></span> <span data-ttu-id="ed0de-143">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-143">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-144">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-144">Required.</span></span> <span data-ttu-id="ed0de-145">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-145">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="ed0de-146">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-146">Required.</span></span> <span data-ttu-id="ed0de-147">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-147">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-148">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-148">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-149">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-149">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-150">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-150">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-151">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-151">Required.</span></span> <span data-ttu-id="ed0de-152">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-152">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-153">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-153">Required.</span></span> <span data-ttu-id="ed0de-154">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-154">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="ed0de-155">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-155">Required.</span></span> <span data-ttu-id="ed0de-156">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-156">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-157">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-157">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-158">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-158">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, parameters As LinkedServiceCreateOrUpdateParameters) As LinkedServiceCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-159">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-159">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-160">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-160">Required.</span></span> <span data-ttu-id="ed0de-161">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-162">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-162">Required.</span></span> <span data-ttu-id="ed0de-163">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="ed0de-163">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ed0de-164">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-164">Required.</span></span> <span data-ttu-id="ed0de-165">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ed0de-165">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-166">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-166">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-167">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-167">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, parameters As LinkedServiceCreateOrUpdateParameters) As Task(Of LinkedServiceCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-168">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-168">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-169">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-169">Required.</span></span> <span data-ttu-id="ed0de-170">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-171">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-171">Required.</span></span> <span data-ttu-id="ed0de-172">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="ed0de-172">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ed0de-173">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-173">Required.</span></span> <span data-ttu-id="ed0de-174">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ed0de-174">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-175">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-175">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-176">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-176">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String, parameters As LinkedServiceCreateOrUpdateWithRawJsonContentParameters) As LinkedServiceCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, linkedServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-177">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-177">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-178">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-178">Required.</span></span> <span data-ttu-id="ed0de-179">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-180">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-180">Required.</span></span> <span data-ttu-id="ed0de-181">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="ed0de-181">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="ed0de-182">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-182">Required.</span></span> <span data-ttu-id="ed0de-183">データ ファクトリの名前には、作成または更新するサービスがリンクされています。</span><span class="sxs-lookup"><span data-stu-id="ed0de-183">The name of the data factory linked service to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ed0de-184">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-184">Required.</span></span> <span data-ttu-id="ed0de-185">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ed0de-185">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-186">作成または、生の json コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-186">Create or update a data factory linkedService with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-187">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-187">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String, parameters As LinkedServiceCreateOrUpdateWithRawJsonContentParameters) As Task(Of LinkedServiceCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, linkedServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-188">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-188">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-189">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-189">Required.</span></span> <span data-ttu-id="ed0de-190">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-190">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-191">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-191">Required.</span></span> <span data-ttu-id="ed0de-192">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="ed0de-192">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="ed0de-193">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-193">Required.</span></span> <span data-ttu-id="ed0de-194">データ ファクトリの名前には、作成または更新するサービスがリンクされています。</span><span class="sxs-lookup"><span data-stu-id="ed0de-194">The name of the data factory linked service to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ed0de-195">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-195">Required.</span></span> <span data-ttu-id="ed0de-196">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ed0de-196">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-197">作成または、生の json コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-197">Create or update a data factory linkedService with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-198">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-198">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-199">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-199">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-200">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-200">Required.</span></span> <span data-ttu-id="ed0de-201">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-201">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-202">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-202">Required.</span></span> <span data-ttu-id="ed0de-203">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-203">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="ed0de-204">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-204">Required.</span></span> <span data-ttu-id="ed0de-205">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-205">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-206">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-206">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-207">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-207">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-208">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-208">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-209">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-209">Required.</span></span> <span data-ttu-id="ed0de-210">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-210">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-211">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-211">Required.</span></span> <span data-ttu-id="ed0de-212">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-212">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="ed0de-213">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-213">Required.</span></span> <span data-ttu-id="ed0de-214">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-214">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-215">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-215">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-216">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-216">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As LinkedServiceGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-217">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-217">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-218">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-218">Required.</span></span> <span data-ttu-id="ed0de-219">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-219">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-220">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-220">Required.</span></span> <span data-ttu-id="ed0de-221">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-221">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="ed0de-222">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-222">Required.</span></span> <span data-ttu-id="ed0de-223">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-223">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-224">データ ファクトリの linkedService インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-224">Gets a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-225">Get データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-225">The Get data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As Task(Of LinkedServiceGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-226">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-226">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-227">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-227">Required.</span></span> <span data-ttu-id="ed0de-228">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-228">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-229">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-229">Required.</span></span> <span data-ttu-id="ed0de-230">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-230">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="ed0de-231">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-231">Required.</span></span> <span data-ttu-id="ed0de-232">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-232">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-233">データ ファクトリの linkedService インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-233">Gets a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-234">Get データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-234">The Get data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As ILinkedServiceOperations, operationStatusLink As String) As LinkedServiceCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-235">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-235">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="ed0de-236">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-236">Required.</span></span> <span data-ttu-id="ed0de-237">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-237">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="ed0de-238">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-238">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As ILinkedServiceOperations, operationStatusLink As String) As Task(Of LinkedServiceCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-239">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-239">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="ed0de-240">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-240">Required.</span></span> <span data-ttu-id="ed0de-241">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-241">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="ed0de-242">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-242">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse List (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse List(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String) As LinkedServiceListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-243">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-243">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-244">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-244">Required.</span></span> <span data-ttu-id="ed0de-245">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-245">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-246">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-246">Required.</span></span> <span data-ttu-id="ed0de-247">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-247">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-248">次のページへのリンクにリンクされたサービス インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-248">Gets the first page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-249">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-249">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of LinkedServiceListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-250">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-250">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed0de-251">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-251">Required.</span></span> <span data-ttu-id="ed0de-252">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="ed0de-252">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="ed0de-253">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-253">Required.</span></span> <span data-ttu-id="ed0de-254">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-254">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-255">次のページへのリンクにリンクされたサービス インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-255">Gets the first page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-256">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-256">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILinkedServiceOperations, nextLink As String) As LinkedServiceListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-257">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-257">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="ed0de-258">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-258">Required.</span></span> <span data-ttu-id="ed0de-259">次のリンクされたサービス ページの url です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-259">The url to the next linked services page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-260">次のページへのリンクにリンクされたサービス インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-260">Gets the next page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-261">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-261">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As ILinkedServiceOperations, nextLink As String) As Task(Of LinkedServiceListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.LinkedServiceOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.LinkedServiceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed0de-262">Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="ed0de-262">Reference to the Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="ed0de-263">必須。</span><span class="sxs-lookup"><span data-stu-id="ed0de-263">Required.</span></span> <span data-ttu-id="ed0de-264">次のリンクされたサービス ページの url です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-264">The url to the next linked services page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed0de-265">次のページへのリンクにリンクされたサービス インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="ed0de-265">Gets the next page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ed0de-266">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="ed0de-266">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>