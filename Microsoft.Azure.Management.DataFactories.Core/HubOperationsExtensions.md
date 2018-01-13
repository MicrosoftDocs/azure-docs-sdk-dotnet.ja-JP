<Type Name="HubOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class HubOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HubOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module HubOperationsExtensions" />
  <TypeSignature Language="F#" Value="type HubOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, parameters As HubCreateOrUpdateParameters) As HubCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-101">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-102">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-102">Required.</span></span> <span data-ttu-id="18396-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-104">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-104">Required.</span></span> <span data-ttu-id="18396-105">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-105">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="18396-106">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-106">Required.</span></span> <span data-ttu-id="18396-107">作成またはハブを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="18396-107">The parameters required to create or update a hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-108">新しいハブ インスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="18396-108">Create a new hub instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-109">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-109">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, parameters As HubCreateOrUpdateParameters) As Task(Of HubCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-110">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-111">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-111">Required.</span></span> <span data-ttu-id="18396-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-113">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-113">Required.</span></span> <span data-ttu-id="18396-114">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-114">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="18396-115">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-115">Required.</span></span> <span data-ttu-id="18396-116">作成またはハブを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="18396-116">The parameters required to create or update a hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-117">新しいハブ インスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="18396-117">Create a new hub instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-118">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-118">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, hubName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, hubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-119">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-120">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-120">Required.</span></span> <span data-ttu-id="18396-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-122">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-122">Required.</span></span> <span data-ttu-id="18396-123">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-123">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="18396-124">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-124">Required.</span></span> <span data-ttu-id="18396-125">ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-125">The name of the hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-126">ハブ インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="18396-126">Delete a hub instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-127">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="18396-127">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, hubName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, hubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-128">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-128">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-129">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-129">Required.</span></span> <span data-ttu-id="18396-130">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-130">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-131">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-131">Required.</span></span> <span data-ttu-id="18396-132">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-132">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="18396-133">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-133">Required.</span></span> <span data-ttu-id="18396-134">ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-134">The name of the hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-135">ハブ インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="18396-135">Delete a hub instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-136">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="18396-136">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, parameters As HubCreateOrUpdateParameters) As HubCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-137">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-137">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-138">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-138">Required.</span></span> <span data-ttu-id="18396-139">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-139">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-140">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-140">Required.</span></span> <span data-ttu-id="18396-141">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-141">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="18396-142">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-142">Required.</span></span> <span data-ttu-id="18396-143">作成またはハブを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="18396-143">The parameters required to create or update a hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-144">新しいハブ インスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="18396-144">Create a new hub instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-145">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-145">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, parameters As HubCreateOrUpdateParameters) As Task(Of HubCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-146">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-146">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-147">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-147">Required.</span></span> <span data-ttu-id="18396-148">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-148">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-149">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-149">Required.</span></span> <span data-ttu-id="18396-150">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-150">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="18396-151">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-151">Required.</span></span> <span data-ttu-id="18396-152">作成またはハブを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="18396-152">The parameters required to create or update a hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-153">新しいハブ インスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="18396-153">Create a new hub instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-154">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-154">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, hubName As String, parameters As HubCreateOrUpdateWithRawJsonContentParameters) As HubCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, hubName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-155">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-155">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-156">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-156">Required.</span></span> <span data-ttu-id="18396-157">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-157">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-158">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-158">Required.</span></span> <span data-ttu-id="18396-159">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-159">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="18396-160">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-160">Required.</span></span> <span data-ttu-id="18396-161">作成または更新するデータ ファクトリのハブの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-161">The name of the data factory hub to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="18396-162">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-162">Required.</span></span> <span data-ttu-id="18396-163">作成またはハブを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="18396-163">The parameters required to create or update a hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-164">新しいハブ インスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="18396-164">Create a new hub instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-165">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-165">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, hubName As String, parameters As HubCreateOrUpdateWithRawJsonContentParameters) As Task(Of HubCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, hubName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-166">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-166">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-167">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-167">Required.</span></span> <span data-ttu-id="18396-168">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-168">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-169">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-169">Required.</span></span> <span data-ttu-id="18396-170">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-170">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="18396-171">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-171">Required.</span></span> <span data-ttu-id="18396-172">作成または更新するデータ ファクトリのハブの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-172">The name of the data factory hub to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="18396-173">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-173">Required.</span></span> <span data-ttu-id="18396-174">作成またはハブを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="18396-174">The parameters required to create or update a hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-175">新しいハブ インスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="18396-175">Create a new hub instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-176">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-176">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, hubName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, hubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-177">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-177">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-178">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-178">Required.</span></span> <span data-ttu-id="18396-179">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-180">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-180">Required.</span></span> <span data-ttu-id="18396-181">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-181">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="18396-182">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-182">Required.</span></span> <span data-ttu-id="18396-183">ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-183">The name of the hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-184">ハブ インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="18396-184">Delete a hub instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-185">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="18396-185">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, hubName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, hubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-186">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-186">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-187">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-187">Required.</span></span> <span data-ttu-id="18396-188">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-188">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-189">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-189">Required.</span></span> <span data-ttu-id="18396-190">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-190">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="18396-191">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-191">Required.</span></span> <span data-ttu-id="18396-192">ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-192">The name of the hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-193">ハブ インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="18396-193">Delete a hub instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-194">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="18396-194">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.HubGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.HubGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, hubName As String) As HubGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.HubGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, hubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.HubGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-195">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-195">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-196">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-196">Required.</span></span> <span data-ttu-id="18396-197">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-197">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-198">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-198">Required.</span></span> <span data-ttu-id="18396-199">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-199">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="18396-200">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-200">Required.</span></span> <span data-ttu-id="18396-201">ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-201">The name of the hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-202">ハブ インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="18396-202">Gets a hub instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-203">Get ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-203">The get hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName, string hubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String, hubName As String) As Task(Of HubGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, hubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-204">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-204">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-205">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-205">Required.</span></span> <span data-ttu-id="18396-206">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-206">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-207">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-207">Required.</span></span> <span data-ttu-id="18396-208">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-208">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="18396-209">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-209">Required.</span></span> <span data-ttu-id="18396-210">ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-210">The name of the hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-211">ハブ インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="18396-211">Gets a hub instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-212">Get ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-212">The get hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IHubOperations, operationStatusLink As String) As HubCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-213">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-213">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="18396-214">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-214">Required.</span></span> <span data-ttu-id="18396-215">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="18396-215">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="18396-216">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-216">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IHubOperations, operationStatusLink As String) As Task(Of HubCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-217">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-217">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="18396-218">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-218">Required.</span></span> <span data-ttu-id="18396-219">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="18396-219">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="18396-220">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-220">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.HubListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.HubListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String) As HubListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.HubListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.HubListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-221">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-221">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-222">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-222">Required.</span></span> <span data-ttu-id="18396-223">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-223">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-224">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-224">Required.</span></span> <span data-ttu-id="18396-225">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-225">The name of the data factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-226">次のページへのリンクがデータ ファクトリのハブ インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="18396-226">Gets the first page of data factory hub instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-227">リストのハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-227">The list hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IHubOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of HubListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-228">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-228">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="18396-229">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-229">Required.</span></span> <span data-ttu-id="18396-230">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="18396-230">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="18396-231">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-231">Required.</span></span> <span data-ttu-id="18396-232">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="18396-232">The name of the data factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-233">次のページへのリンクがデータ ファクトリのハブ インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="18396-233">Gets the first page of data factory hub instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-234">リストのハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-234">The list hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.HubListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.HubListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IHubOperations, nextLink As String) As HubListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.HubListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.HubListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-235">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-235">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="18396-236">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-236">Required.</span></span> <span data-ttu-id="18396-237">次のデータ ファクトリのハブ ページの url です。</span><span class="sxs-lookup"><span data-stu-id="18396-237">The url to the next data factory hubs page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-238">次のページへのリンクがデータ ファクトリのハブ インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="18396-238">Gets the next page of data factory hub instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-239">リストのハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-239">The list hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IHubOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IHubOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IHubOperations, nextLink As String) As Task(Of HubListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IHubOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.HubOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IHubOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="18396-240">Microsoft.Azure.Management.DataFactories.Core.IHubOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="18396-240">Reference to the Microsoft.Azure.Management.DataFactories.Core.IHubOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="18396-241">必須。</span><span class="sxs-lookup"><span data-stu-id="18396-241">Required.</span></span> <span data-ttu-id="18396-242">次のデータ ファクトリのハブ ページの url です。</span><span class="sxs-lookup"><span data-stu-id="18396-242">The url to the next data factory hubs page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="18396-243">次のページへのリンクがデータ ファクトリのハブ インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="18396-243">Gets the next page of data factory hub instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="18396-244">リストのハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="18396-244">The list hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>