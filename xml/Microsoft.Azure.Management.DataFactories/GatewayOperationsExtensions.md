<Type Name="GatewayOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class GatewayOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GatewayOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-101">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-102">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-102">Required.</span></span> <span data-ttu-id="c0497-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-104">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-104">Required.</span></span> <span data-ttu-id="c0497-105">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-105">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0497-106">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-106">Required.</span></span> <span data-ttu-id="c0497-107">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0497-107">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-108">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0497-108">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-109">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-109">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-110">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-111">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-111">Required.</span></span> <span data-ttu-id="c0497-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-113">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-113">Required.</span></span> <span data-ttu-id="c0497-114">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-114">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0497-115">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-115">Required.</span></span> <span data-ttu-id="c0497-116">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0497-116">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-117">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0497-117">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-118">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-118">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-119">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-120">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-120">Required.</span></span> <span data-ttu-id="c0497-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-122">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-122">Required.</span></span> <span data-ttu-id="c0497-123">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-123">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-124">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-124">Required.</span></span> <span data-ttu-id="c0497-125">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="c0497-125">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-126">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="c0497-126">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-127">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="c0497-127">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-128">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-128">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-129">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-129">Required.</span></span> <span data-ttu-id="c0497-130">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-130">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-131">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-131">Required.</span></span> <span data-ttu-id="c0497-132">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-132">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-133">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-133">Required.</span></span> <span data-ttu-id="c0497-134">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="c0497-134">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-135">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="c0497-135">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-136">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="c0497-136">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-137">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-137">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-138">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-138">Required.</span></span> <span data-ttu-id="c0497-139">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-139">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-140">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-140">Required.</span></span> <span data-ttu-id="c0497-141">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-141">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0497-142">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-142">Required.</span></span> <span data-ttu-id="c0497-143">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0497-143">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-144">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0497-144">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-145">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-145">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-146">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-146">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-147">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-147">Required.</span></span> <span data-ttu-id="c0497-148">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-148">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-149">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-149">Required.</span></span> <span data-ttu-id="c0497-150">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-150">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0497-151">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-151">Required.</span></span> <span data-ttu-id="c0497-152">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0497-152">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-153">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0497-153">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-154">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-154">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-155">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-155">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-156">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-156">Required.</span></span> <span data-ttu-id="c0497-157">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-157">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-158">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-158">Required.</span></span> <span data-ttu-id="c0497-159">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-159">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-160">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-160">Required.</span></span> <span data-ttu-id="c0497-161">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="c0497-161">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-162">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="c0497-162">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-163">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="c0497-163">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-164">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-164">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-165">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-165">Required.</span></span> <span data-ttu-id="c0497-166">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-166">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-167">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-167">Required.</span></span> <span data-ttu-id="c0497-168">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-168">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-169">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-169">Required.</span></span> <span data-ttu-id="c0497-170">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="c0497-170">Name of the gateway to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-171">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="c0497-171">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-172">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="c0497-172">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse Get (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse Get(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-173">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-173">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-174">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-174">Required.</span></span> <span data-ttu-id="c0497-175">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-175">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-176">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-176">Required.</span></span> <span data-ttu-id="c0497-177">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-177">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-178">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-178">Required.</span></span> <span data-ttu-id="c0497-179">取得するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="c0497-179">Name of the gateway to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-180">データ ファクトリのゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0497-180">Gets a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-181">Get データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-181">The Get data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-182">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-182">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-183">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-183">Required.</span></span> <span data-ttu-id="c0497-184">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-184">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-185">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-185">Required.</span></span> <span data-ttu-id="c0497-186">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-186">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-187">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-187">Required.</span></span> <span data-ttu-id="c0497-188">取得するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="c0497-188">Name of the gateway to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-189">データ ファクトリのゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0497-189">Gets a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-190">Get データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-190">The Get data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IGatewayOperations, operationStatusLink As String) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-191">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-191">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="c0497-192">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-192">Required.</span></span> <span data-ttu-id="c0497-193">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="c0497-193">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-194">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="c0497-194">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="c0497-195">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="c0497-195">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-196">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-196">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IGatewayOperations, operationStatusLink As String) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-197">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-197">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="c0497-198">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-198">Required.</span></span> <span data-ttu-id="c0497-199">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="c0497-199">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-200">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="c0497-200">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="c0497-201">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="c0497-201">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-202">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-202">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse List (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse List(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String) As GatewayListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-203">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-203">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-204">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-204">Required.</span></span> <span data-ttu-id="c0497-205">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-205">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-206">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-206">Required.</span></span> <span data-ttu-id="c0497-207">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-207">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-208">データ ファクトリの下にあるすべてのゲートウェイを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0497-208">List all gateways under a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-209">一覧データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-209">The List data factory gateways operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of GatewayListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-210">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-210">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-211">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-211">Required.</span></span> <span data-ttu-id="c0497-212">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-212">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-213">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-213">Required.</span></span> <span data-ttu-id="c0497-214">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-214">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-215">データ ファクトリの下にあるすべてのゲートウェイを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0497-215">List all gateways under a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-216">一覧データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-216">The List data factory gateways operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse ListAuthKeys (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse ListAuthKeys(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAuthKeys(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthKeys (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayListAuthKeysResponse" />
      <MemberSignature Language="F#" Value="static member ListAuthKeys : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAuthKeys (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-217">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-217">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-218">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-218">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-219">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-219">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-220">認証キーの一覧表示するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="c0497-220">The name of the gateway to list auth keys.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-221">ゲートウェイの認証キーの一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0497-221">List auth keys of the gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-222">一覧データ ファクトリのゲートウェイ認証キーの操作の応答です。</span><span class="sxs-lookup"><span data-stu-id="c0497-222">The List data factory gateway auth keys operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAuthKeysAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthKeysAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayListAuthKeysResponse)" />
      <MemberSignature Language="F#" Value="static member ListAuthKeysAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.ListAuthKeysAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-223">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-223">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-224">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-224">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-225">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-225">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-226">認証キーの一覧表示するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="c0497-226">The name of the gateway to list auth keys.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-227">ゲートウェイの認証キーの一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c0497-227">List auth keys of the gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-228">一覧データ ファクトリのゲートウェイ認証キーの操作の応答です。</span><span class="sxs-lookup"><span data-stu-id="c0497-228">The List data factory gateway auth keys operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse RegenerateAuthKey (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse RegenerateAuthKey(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateAuthKey(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateAuthKey (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String, parameters As GatewayRegenerateAuthKeyParameters) As GatewayRegenerateAuthKeyResponse" />
      <MemberSignature Language="F#" Value="static member RegenerateAuthKey : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateAuthKey (operations, resourceGroupName, dataFactoryName, gatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-229">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-229">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-230">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-230">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-231">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-231">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-232">認証キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0497-232">The name of the gateway to regenerate auth key.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0497-233">再生成するゲートウェイ認証キーの名前。</span><span class="sxs-lookup"><span data-stu-id="c0497-233">Name of the gateway auth key to be regenerated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-234">ゲートウェイ認証キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="c0497-234">Regenerate gateway auth key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-235">再生成のゲートウェイ認証キー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0497-235">The regenerate gateway auth key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName, class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateAuthKeyAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateAuthKeyAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String, parameters As GatewayRegenerateAuthKeyParameters) As Task(Of GatewayRegenerateAuthKeyResponse)" />
      <MemberSignature Language="F#" Value="static member RegenerateAuthKeyAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateAuthKeyAsync (operations, resourceGroupName, dataFactoryName, gatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-236">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-236">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-237">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-237">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-238">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-238">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-239">認証キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0497-239">The name of the gateway to regenerate auth key.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0497-240">再生成するゲートウェイ認証キーの名前。</span><span class="sxs-lookup"><span data-stu-id="c0497-240">Name of the gateway auth key to be regenerated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-241">ゲートウェイ認証キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="c0497-241">Regenerate gateway auth key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-242">再生成のゲートウェイ認証キー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0497-242">The regenerate gateway auth key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse RegenerateKey (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse RegenerateKey(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateKey(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayRegenerateKeyResponse" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateKey (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-243">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-243">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-244">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-244">Required.</span></span> <span data-ttu-id="c0497-245">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-245">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-246">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-246">Required.</span></span> <span data-ttu-id="c0497-247">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-247">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-248">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-248">Required.</span></span> <span data-ttu-id="c0497-249">キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0497-249">The name of the gateway to regenerate key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-250">ゲートウェイのキーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="c0497-250">Regenerate gateway key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-251">再生成するゲートウェイのキー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0497-251">The regenerate gateway key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeyAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayRegenerateKeyResponse)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RegenerateKeyAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-252">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-252">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-253">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-253">Required.</span></span> <span data-ttu-id="c0497-254">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-254">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-255">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-255">Required.</span></span> <span data-ttu-id="c0497-256">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-256">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-257">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-257">Required.</span></span> <span data-ttu-id="c0497-258">キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0497-258">The name of the gateway to regenerate key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-259">ゲートウェイのキーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="c0497-259">Regenerate gateway key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-260">再生成するゲートウェイのキー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0497-260">The regenerate gateway key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveConnectionInfo">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse RetrieveConnectionInfo (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse RetrieveConnectionInfo(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RetrieveConnectionInfo(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RetrieveConnectionInfo (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As GatewayConnectionInfoRetrieveResponse" />
      <MemberSignature Language="F#" Value="static member RetrieveConnectionInfo : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RetrieveConnectionInfo (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-261">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-261">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-262">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-262">Required.</span></span> <span data-ttu-id="c0497-263">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-263">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-264">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-264">Required.</span></span> <span data-ttu-id="c0497-265">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-265">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-266">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-266">Required.</span></span> <span data-ttu-id="c0497-267">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0497-267">Name of the gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-268">ゲートウェイの接続情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c0497-268">Retrieve gateway connection information.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-269">ゲートウェイの接続情報を取得する操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0497-269">The retrieve gateway connection information operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveConnectionInfoAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RetrieveConnectionInfoAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RetrieveConnectionInfoAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, gatewayName As String) As Task(Of GatewayConnectionInfoRetrieveResponse)" />
      <MemberSignature Language="F#" Value="static member RetrieveConnectionInfoAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.RetrieveConnectionInfoAsync (operations, resourceGroupName, dataFactoryName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-270">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-270">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-271">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-271">Required.</span></span> <span data-ttu-id="c0497-272">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-272">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-273">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-273">Required.</span></span> <span data-ttu-id="c0497-274">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-274">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="c0497-275">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-275">Required.</span></span> <span data-ttu-id="c0497-276">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0497-276">Name of the gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-277">ゲートウェイの接続情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c0497-277">Retrieve gateway connection information.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-278">ゲートウェイの接続情報を取得する操作応答です。</span><span class="sxs-lookup"><span data-stu-id="c0497-278">The retrieve gateway connection information operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse Update (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse Update(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Update(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As GatewayCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.Update (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-279">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-279">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-280">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-280">Required.</span></span> <span data-ttu-id="c0497-281">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-281">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-282">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-282">Required.</span></span> <span data-ttu-id="c0497-283">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-283">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0497-284">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-284">Required.</span></span> <span data-ttu-id="c0497-285">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0497-285">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-286">データ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0497-286">Update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-287">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-287">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync (this Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync(class Microsoft.Azure.Management.DataFactories.IGatewayOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataFactories.IGatewayOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateAsync (operations As IGatewayOperations, resourceGroupName As String, dataFactoryName As String, parameters As GatewayCreateOrUpdateParameters) As Task(Of GatewayCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataFactories.IGatewayOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.GatewayOperationsExtensions.UpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IGatewayOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0497-288">Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c0497-288">Reference to the Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0497-289">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-289">Required.</span></span> <span data-ttu-id="c0497-290">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c0497-290">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c0497-291">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-291">Required.</span></span> <span data-ttu-id="c0497-292">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c0497-292">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0497-293">必須。</span><span class="sxs-lookup"><span data-stu-id="c0497-293">Required.</span></span> <span data-ttu-id="c0497-294">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0497-294">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0497-295">データ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0497-295">Update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0497-296">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c0497-296">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>