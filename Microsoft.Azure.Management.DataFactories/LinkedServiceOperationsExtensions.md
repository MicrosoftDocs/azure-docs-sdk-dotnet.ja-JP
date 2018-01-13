<Type Name="LinkedServiceOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LinkedServiceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LinkedServiceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions" />
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
    <summary>
            <span data-ttu-id="68d4f-101">データ ファクトリ linkedServices を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-101">Operations for managing data factory linkedServices.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, parameters As LinkedServiceCreateOrUpdateParameters) As LinkedServiceCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-102">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-102">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-103">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-103">Required.</span></span> <span data-ttu-id="68d4f-104">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-104">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-105">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-105">Required.</span></span> <span data-ttu-id="68d4f-106">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-106">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="68d4f-107">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-107">Required.</span></span> <span data-ttu-id="68d4f-108">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="68d4f-108">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-109">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-109">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-110">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-110">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, parameters As LinkedServiceCreateOrUpdateParameters) As Task(Of LinkedServiceCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-111">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-111">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-112">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-112">Required.</span></span> <span data-ttu-id="68d4f-113">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-113">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-114">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-114">Required.</span></span> <span data-ttu-id="68d4f-115">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-115">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="68d4f-116">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-116">Required.</span></span> <span data-ttu-id="68d4f-117">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="68d4f-117">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-118">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-118">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-119">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-119">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContent (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String, parameters As LinkedServiceCreateOrUpdateWithRawJsonContentParameters) As LinkedServiceCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, linkedServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-120">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-120">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-121">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-121">Required.</span></span> <span data-ttu-id="68d4f-122">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-122">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-123">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-123">Required.</span></span> <span data-ttu-id="68d4f-124">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-124">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="68d4f-125">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-125">Required.</span></span> <span data-ttu-id="68d4f-126">データ ファクトリの作成または更新するリンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-126">The name of the data factory Linked Service to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="68d4f-127">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-127">Required.</span></span> <span data-ttu-id="68d4f-128">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="68d4f-128">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-129">作成または、生の json コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-129">Create or update a data factory linkedService with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-130">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-130">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContentAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String, parameters As LinkedServiceCreateOrUpdateWithRawJsonContentParameters) As Task(Of LinkedServiceCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, linkedServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-131">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-131">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-132">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-132">Required.</span></span> <span data-ttu-id="68d4f-133">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-133">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-134">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-134">Required.</span></span> <span data-ttu-id="68d4f-135">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-135">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="68d4f-136">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-136">Required.</span></span> <span data-ttu-id="68d4f-137">データ ファクトリの作成または更新するリンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-137">The name of the data factory Linked Service to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="68d4f-138">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-138">Required.</span></span> <span data-ttu-id="68d4f-139">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="68d4f-139">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-140">作成または、生の json コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-140">Create or update a data factory linkedService with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-141">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-141">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-142">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-142">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-143">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-143">Required.</span></span> <span data-ttu-id="68d4f-144">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-144">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-145">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-145">Required.</span></span> <span data-ttu-id="68d4f-146">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-146">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="68d4f-147">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-147">Required.</span></span> <span data-ttu-id="68d4f-148">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-148">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-149">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-149">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-150">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-150">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-151">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-151">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-152">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-152">Required.</span></span> <span data-ttu-id="68d4f-153">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-153">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-154">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-154">Required.</span></span> <span data-ttu-id="68d4f-155">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-155">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="68d4f-156">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-156">Required.</span></span> <span data-ttu-id="68d4f-157">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-157">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-158">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-158">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-159">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-159">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, parameters As LinkedServiceCreateOrUpdateParameters) As LinkedServiceCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-160">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-160">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-161">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-161">Required.</span></span> <span data-ttu-id="68d4f-162">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-162">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-163">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-163">Required.</span></span> <span data-ttu-id="68d4f-164">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-164">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="68d4f-165">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-165">Required.</span></span> <span data-ttu-id="68d4f-166">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="68d4f-166">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-167">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-167">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-168">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-168">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, parameters As LinkedServiceCreateOrUpdateParameters) As Task(Of LinkedServiceCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-169">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-169">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-170">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-170">Required.</span></span> <span data-ttu-id="68d4f-171">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-171">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-172">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-172">Required.</span></span> <span data-ttu-id="68d4f-173">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-173">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="68d4f-174">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-174">Required.</span></span> <span data-ttu-id="68d4f-175">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="68d4f-175">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-176">作成またはデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-176">Create or update a data factory linkedService.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-177">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-177">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String, parameters As LinkedServiceCreateOrUpdateWithRawJsonContentParameters) As LinkedServiceCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, linkedServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-178">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-178">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-179">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-179">Required.</span></span> <span data-ttu-id="68d4f-180">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-180">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-181">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-181">Required.</span></span> <span data-ttu-id="68d4f-182">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-182">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="68d4f-183">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-183">Required.</span></span> <span data-ttu-id="68d4f-184">データ ファクトリの作成または更新するリンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-184">The name of the data factory Linked Service to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="68d4f-185">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-185">Required.</span></span> <span data-ttu-id="68d4f-186">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="68d4f-186">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-187">作成または、生の json コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-187">Create or update a data factory linkedService with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-188">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-188">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String, parameters As LinkedServiceCreateOrUpdateWithRawJsonContentParameters) As Task(Of LinkedServiceCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, linkedServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-189">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-189">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-190">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-190">Required.</span></span> <span data-ttu-id="68d4f-191">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-191">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-192">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-192">Required.</span></span> <span data-ttu-id="68d4f-193">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-193">The name of the data factory.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="68d4f-194">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-194">Required.</span></span> <span data-ttu-id="68d4f-195">データ ファクトリの作成または更新するリンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="68d4f-195">The name of the data factory Linked Service to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="68d4f-196">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-196">Required.</span></span> <span data-ttu-id="68d4f-197">作成またはデータ ファクトリ linkedService を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="68d4f-197">The parameters required to create or update a data factory linkedService.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-198">作成または、生の json コンテンツを持つデータ ファクトリ linkedService を更新します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-198">Create or update a data factory linkedService with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-199">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-199">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-200">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-200">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-201">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-201">Required.</span></span> <span data-ttu-id="68d4f-202">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-202">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-203">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-203">Required.</span></span> <span data-ttu-id="68d4f-204">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-204">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="68d4f-205">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-205">Required.</span></span> <span data-ttu-id="68d4f-206">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-206">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-207">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-207">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-208">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-208">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-209">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-209">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-210">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-210">Required.</span></span> <span data-ttu-id="68d4f-211">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-211">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-212">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-212">Required.</span></span> <span data-ttu-id="68d4f-213">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-213">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="68d4f-214">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-214">Required.</span></span> <span data-ttu-id="68d4f-215">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-215">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-216">データ ファクトリの linkedService インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-216">Delete a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-217">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-217">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse Get (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse Get(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As LinkedServiceGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-218">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-218">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-219">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-219">Required.</span></span> <span data-ttu-id="68d4f-220">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-220">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-221">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-221">Required.</span></span> <span data-ttu-id="68d4f-222">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-222">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="68d4f-223">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-223">Required.</span></span> <span data-ttu-id="68d4f-224">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-224">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-225">データ ファクトリの linkedService インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-225">Gets a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-226">Get データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-226">The Get data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName, string linkedServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String, linkedServiceName As String) As Task(Of LinkedServiceGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, linkedServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-227">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-227">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-228">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-228">Required.</span></span> <span data-ttu-id="68d4f-229">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-229">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-230">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-230">Required.</span></span> <span data-ttu-id="68d4f-231">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-231">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="68d4f-232">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-232">Required.</span></span> <span data-ttu-id="68d4f-233">一意のデータ ファクトリの linkedService 名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-233">A unique data factory linkedService name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-234">データ ファクトリの linkedService インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-234">Gets a data factory linkedService instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-235">Get データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-235">The Get data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As ILinkedServiceOperations, operationStatusLink As String) As LinkedServiceCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-236">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-236">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="68d4f-237">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-237">Required.</span></span> <span data-ttu-id="68d4f-238">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-238">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="68d4f-239">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-239">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As ILinkedServiceOperations, operationStatusLink As String) As Task(Of LinkedServiceCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-240">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-240">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="68d4f-241">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-241">Required.</span></span> <span data-ttu-id="68d4f-242">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-242">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="68d4f-243">作成または更新データ ファクトリ linkedService 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-243">The create or update data factory linkedService operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse List (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse List(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String) As LinkedServiceListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-244">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-244">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-245">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-245">Required.</span></span> <span data-ttu-id="68d4f-246">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-246">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-247">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-247">Required.</span></span> <span data-ttu-id="68d4f-248">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-248">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-249">次のページへのリンクにリンクされたサービス インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-249">Gets the first page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-250">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-250">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As ILinkedServiceOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of LinkedServiceListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-251">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-251">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68d4f-252">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-252">Required.</span></span> <span data-ttu-id="68d4f-253">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="68d4f-253">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="68d4f-254">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-254">Required.</span></span> <span data-ttu-id="68d4f-255">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-255">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-256">次のページへのリンクにリンクされたサービス インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-256">Gets the first page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-257">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-257">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse ListNext (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse ListNext(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILinkedServiceOperations, nextLink As String) As LinkedServiceListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-258">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-258">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="68d4f-259">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-259">Required.</span></span> <span data-ttu-id="68d4f-260">次のリンクされたサービス ページの url です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-260">The url to the next linked services page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-261">次のページへのリンクにリンクされたサービス インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-261">Gets the next page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-262">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-262">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As ILinkedServiceOperations, nextLink As String) As Task(Of LinkedServiceListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.LinkedServiceOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.LinkedServiceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68d4f-263">Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="68d4f-263">Reference to the Microsoft.Azure.Management.DataFactories.ILinkedServiceOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="68d4f-264">必須。</span><span class="sxs-lookup"><span data-stu-id="68d4f-264">Required.</span></span> <span data-ttu-id="68d4f-265">次のリンクされたサービス ページの url です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-265">The url to the next linked services page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68d4f-266">次のページへのリンクにリンクされたサービス インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="68d4f-266">Gets the next page of linked service instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="68d4f-267">一覧データ ファクトリ linkedServices 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="68d4f-267">The List data factory linkedServices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>