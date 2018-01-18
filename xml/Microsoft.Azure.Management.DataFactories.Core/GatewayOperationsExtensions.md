<Type Name="GatewayOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class GatewayOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GatewayOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GatewayOperationsExtensions" />
  <TypeSignature Language="F#" Value="type GatewayOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-101">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-102">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-102">Required.</span></span> <span data-ttu-id="1a8b4-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-104">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-104">Required.</span></span> <span data-ttu-id="1a8b4-105">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-105">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8b4-106">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-106">Required.</span></span> <span data-ttu-id="1a8b4-107">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-107">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-108">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-108">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-109">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-109">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-110">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-111">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-111">Required.</span></span> <span data-ttu-id="1a8b4-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-113">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-113">Required.</span></span> <span data-ttu-id="1a8b4-114">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-114">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8b4-115">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-115">Required.</span></span> <span data-ttu-id="1a8b4-116">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-116">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-117">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-117">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-118">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-118">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-119">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-120">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-120">Required.</span></span> <span data-ttu-id="1a8b4-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-122">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-122">Required.</span></span> <span data-ttu-id="1a8b4-123">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-123">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-124">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-124">Required.</span></span> <span data-ttu-id="1a8b4-125">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-125">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-126">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-126">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-127">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-127">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-128">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-128">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-129">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-129">Required.</span></span> <span data-ttu-id="1a8b4-130">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-130">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-131">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-131">Required.</span></span> <span data-ttu-id="1a8b4-132">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-132">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-133">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-133">Required.</span></span> <span data-ttu-id="1a8b4-134">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-134">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-135">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-135">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-136">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-136">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-137">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-137">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-138">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-138">Required.</span></span> <span data-ttu-id="1a8b4-139">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-139">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-140">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-140">Required.</span></span> <span data-ttu-id="1a8b4-141">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-141">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8b4-142">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-142">Required.</span></span> <span data-ttu-id="1a8b4-143">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-143">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-144">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-144">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-145">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-145">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-146">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-146">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-147">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-147">Required.</span></span> <span data-ttu-id="1a8b4-148">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-148">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-149">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-149">Required.</span></span> <span data-ttu-id="1a8b4-150">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-150">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8b4-151">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-151">Required.</span></span> <span data-ttu-id="1a8b4-152">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-152">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-153">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-153">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-154">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-154">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-155">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-155">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-156">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-156">Required.</span></span> <span data-ttu-id="1a8b4-157">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-157">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-158">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-158">Required.</span></span> <span data-ttu-id="1a8b4-159">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-159">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-160">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-160">Required.</span></span> <span data-ttu-id="1a8b4-161">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-161">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-162">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-162">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-163">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="1a8b4-163">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-164">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-164">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-165">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-165">Required.</span></span> <span data-ttu-id="1a8b4-166">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-166">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-167">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-167">Required.</span></span> <span data-ttu-id="1a8b4-168">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-168">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-169">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-169">Required.</span></span> <span data-ttu-id="1a8b4-170">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-170">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-171">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-171">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-172">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="1a8b4-172">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-173">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-173">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-174">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-174">Required.</span></span> <span data-ttu-id="1a8b4-175">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-175">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-176">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-176">Required.</span></span> <span data-ttu-id="1a8b4-177">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-177">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-178">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-178">Required.</span></span> <span data-ttu-id="1a8b4-179">取得するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-179">Name of the gateway to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-180">データ ファクトリのゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-180">Gets a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-181">Get データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-181">The Get data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-182">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-182">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-183">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-183">Required.</span></span> <span data-ttu-id="1a8b4-184">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-184">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-185">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-185">Required.</span></span> <span data-ttu-id="1a8b4-186">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-186">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-187">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-187">Required.</span></span> <span data-ttu-id="1a8b4-188">取得するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-188">Name of the gateway to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-189">データ ファクトリのゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-189">Gets a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-190">Get データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-190">The Get data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IGatewayOperations, operationStatusLink As String) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-191">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-191">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="1a8b4-192">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-192">Required.</span></span> <span data-ttu-id="1a8b4-193">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-193">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-194">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-194">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="1a8b4-195">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-195">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-196">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-196">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IGatewayOperations, operationStatusLink As String) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-197">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-197">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="1a8b4-198">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-198">Required.</span></span> <span data-ttu-id="1a8b4-199">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-199">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-200">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-200">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="1a8b4-201">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-201">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-202">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-202">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String) As GatewayListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-203">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-203">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-204">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-204">Required.</span></span> <span data-ttu-id="1a8b4-205">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-205">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-206">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-206">Required.</span></span> <span data-ttu-id="1a8b4-207">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-207">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-208">データ ファクトリの下にあるすべてのゲートウェイを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-208">List all gateways under a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-209">一覧データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-209">The List data factory gateways operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of GatewayListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-210">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-210">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-211">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-211">Required.</span></span> <span data-ttu-id="1a8b4-212">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-212">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-213">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-213">Required.</span></span> <span data-ttu-id="1a8b4-214">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-214">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-215">データ ファクトリの下にあるすべてのゲートウェイを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-215">List all gateways under a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-216">一覧データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-216">The List data factory gateways operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse ListAuthKeys (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse ListAuthKeys(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.ListAuthKeys(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthKeys (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayListAuthKeysResponse" />
      <MemberSignature Language="F#" Value="static member ListAuthKeys : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.ListAuthKeys (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-217">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-217">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-218">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-218">Required.</span></span> <span data-ttu-id="1a8b4-219">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-219">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-220">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-220">Required.</span></span> <span data-ttu-id="1a8b4-221">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-221">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-222">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-222">Required.</span></span> <span data-ttu-id="1a8b4-223">認証キーの一覧表示するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-223">The name of the gateway to list auth keys.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-224">ゲートウェイ認証キーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-224">List gateway authentication keys.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-225">一覧のゲートウェイ認証キーの操作の応答です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-225">The list gateway auth keys operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.ListAuthKeysAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthKeysAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayListAuthKeysResponse)" />
      <MemberSignature Language="F#" Value="static member ListAuthKeysAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.ListAuthKeysAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-226">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-226">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-227">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-227">Required.</span></span> <span data-ttu-id="1a8b4-228">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-228">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-229">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-229">Required.</span></span> <span data-ttu-id="1a8b4-230">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-230">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-231">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-231">Required.</span></span> <span data-ttu-id="1a8b4-232">認証キーの一覧表示するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-232">The name of the gateway to list auth keys.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-233">ゲートウェイ認証キーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-233">List gateway authentication keys.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-234">一覧のゲートウェイ認証キーの操作の応答です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-234">The list gateway auth keys operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse RegenerateAuthKey (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse RegenerateAuthKey(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RegenerateAuthKey(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateAuthKey (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String, parameters As GatewayRegenerateAuthKeyParameters) As GatewayRegenerateAuthKeyResponse" />
      <MemberSignature Language="F#" Value="static member RegenerateAuthKey : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RegenerateAuthKey (operations, resourceGroupName, dataFactoryName, gatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-235">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-235">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-236">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-236">Required.</span></span> <span data-ttu-id="1a8b4-237">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-237">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-238">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-238">Required.</span></span> <span data-ttu-id="1a8b4-239">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-239">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-240">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-240">Required.</span></span> <span data-ttu-id="1a8b4-241">キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-241">The name of the gateway to regenerate key.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8b4-242">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-242">Required.</span></span> <span data-ttu-id="1a8b4-243">再生成する認証キーの名前。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-243">The name of the authentication key to be regenerated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-244">ゲートウェイ認証キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-244">Regenerate gateway authentication key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-245">再生成のゲートウェイ認証キー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-245">The regenerate gateway auth key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RegenerateAuthKeyAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateAuthKeyAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String, parameters As GatewayRegenerateAuthKeyParameters) As Task(Of GatewayRegenerateAuthKeyResponse)" />
      <MemberSignature Language="F#" Value="static member RegenerateAuthKeyAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RegenerateAuthKeyAsync (operations, resourceGroupName, dataFactoryName, gatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-246">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-246">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-247">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-247">Required.</span></span> <span data-ttu-id="1a8b4-248">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-248">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-249">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-249">Required.</span></span> <span data-ttu-id="1a8b4-250">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-250">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-251">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-251">Required.</span></span> <span data-ttu-id="1a8b4-252">キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-252">The name of the gateway to regenerate key.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8b4-253">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-253">Required.</span></span> <span data-ttu-id="1a8b4-254">再生成する認証キーの名前。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-254">The name of the authentication key to be regenerated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-255">ゲートウェイ認証キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-255">Regenerate gateway authentication key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-256">再生成のゲートウェイ認証キー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-256">The regenerate gateway auth key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse RegenerateKey (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse RegenerateKey(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayRegenerateKeyResponse" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RegenerateKey (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-257">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-257">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-258">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-258">Required.</span></span> <span data-ttu-id="1a8b4-259">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-259">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-260">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-260">Required.</span></span> <span data-ttu-id="1a8b4-261">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-261">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-262">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-262">Required.</span></span> <span data-ttu-id="1a8b4-263">キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-263">The name of the gateway to regenerate key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-264">ゲートウェイのキーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-264">Regenerate gateway key.</span></span> <span data-ttu-id="1a8b4-265">この API は廃止されており、RegenerateAuthKey を代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-265">This API has been deprecated and RegenerateAuthKey should be used instead.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-266">再生成するゲートウェイのキー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-266">The regenerate gateway key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeyAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayRegenerateKeyResponse)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-267">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-267">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-268">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-268">Required.</span></span> <span data-ttu-id="1a8b4-269">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-269">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-270">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-270">Required.</span></span> <span data-ttu-id="1a8b4-271">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-271">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-272">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-272">Required.</span></span> <span data-ttu-id="1a8b4-273">キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-273">The name of the gateway to regenerate key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-274">ゲートウェイのキーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-274">Regenerate gateway key.</span></span> <span data-ttu-id="1a8b4-275">この API は廃止されており、RegenerateAuthKey を代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-275">This API has been deprecated and RegenerateAuthKey should be used instead.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-276">再生成するゲートウェイのキー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-276">The regenerate gateway key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveConnectionInfo">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse RetrieveConnectionInfo (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse RetrieveConnectionInfo(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RetrieveConnectionInfo(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RetrieveConnectionInfo (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayConnectionInfoRetrieveResponse" />
      <MemberSignature Language="F#" Value="static member RetrieveConnectionInfo : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RetrieveConnectionInfo (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-277">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-277">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-278">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-278">Required.</span></span> <span data-ttu-id="1a8b4-279">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-279">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-280">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-280">Required.</span></span> <span data-ttu-id="1a8b4-281">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-281">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-282">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-282">Required.</span></span> <span data-ttu-id="1a8b4-283">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-283">Name of the gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-284">ゲートウェイの接続情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-284">Retrieve gateway connection information.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-285">ゲートウェイの接続情報を取得する操作応答です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-285">The retrieve gateway connection information operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveConnectionInfoAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RetrieveConnectionInfoAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RetrieveConnectionInfoAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayConnectionInfoRetrieveResponse)" />
      <MemberSignature Language="F#" Value="static member RetrieveConnectionInfoAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.RetrieveConnectionInfoAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-286">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-286">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-287">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-287">Required.</span></span> <span data-ttu-id="1a8b4-288">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-288">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-289">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-289">Required.</span></span> <span data-ttu-id="1a8b4-290">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-290">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="1a8b4-291">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-291">Required.</span></span> <span data-ttu-id="1a8b4-292">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-292">Name of the gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-293">ゲートウェイの接続情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-293">Retrieve gateway connection information.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-294">ゲートウェイの接続情報を取得する操作応答です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-294">The retrieve gateway connection information operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse Update (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse Update(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.Update(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.Update (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-295">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-295">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-296">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-296">Required.</span></span> <span data-ttu-id="1a8b4-297">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-297">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-298">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-298">Required.</span></span> <span data-ttu-id="1a8b4-299">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-299">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8b4-300">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-300">Required.</span></span> <span data-ttu-id="1a8b4-301">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-301">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-302">データ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-302">Update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-303">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-303">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.GatewayOperationsExtensions.UpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1a8b4-304">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-304">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1a8b4-305">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-305">Required.</span></span> <span data-ttu-id="1a8b4-306">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-306">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1a8b4-307">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-307">Required.</span></span> <span data-ttu-id="1a8b4-308">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-308">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1a8b4-309">必須。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-309">Required.</span></span> <span data-ttu-id="1a8b4-310">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-310">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1a8b4-311">データ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-311">Update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1a8b4-312">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="1a8b4-312">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>