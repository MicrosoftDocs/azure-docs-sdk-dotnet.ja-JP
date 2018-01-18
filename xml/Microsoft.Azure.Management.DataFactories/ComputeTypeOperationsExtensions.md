<Type Name="ComputeTypeOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ComputeTypeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ComputeTypeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ComputeTypeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ComputeTypeOperationsExtensions = class" />
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
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, computeTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-101">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-101">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-102">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-102">Required.</span></span> <span data-ttu-id="143b9-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-104">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-104">Required.</span></span> <span data-ttu-id="143b9-105">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-105">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="143b9-106">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-106">Required.</span></span> <span data-ttu-id="143b9-107">ComputeType の名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-107">The name of the computeType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-108">ComputeType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="143b9-108">Delete an ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-109">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="143b9-109">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, computeTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-110">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-110">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-111">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-111">Required.</span></span> <span data-ttu-id="143b9-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-113">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-113">Required.</span></span> <span data-ttu-id="143b9-114">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-114">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="143b9-115">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-115">Required.</span></span> <span data-ttu-id="143b9-116">ComputeType の名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-116">The name of the computeType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-117">ComputeType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="143b9-117">Delete an ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-118">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="143b9-118">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeCreateOrUpdateParameters) As ComputeTypeCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-119">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-119">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-120">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-120">Required.</span></span> <span data-ttu-id="143b9-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-122">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-122">Required.</span></span> <span data-ttu-id="143b9-123">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-123">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="143b9-124">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-124">Required.</span></span> <span data-ttu-id="143b9-125">作成または ComputeType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="143b9-125">The parameters required to create or update an ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-126">作成または、ComputeType を更新します。</span><span class="sxs-lookup"><span data-stu-id="143b9-126">Create or update an ComputeType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-127">作成または更新 ComputeType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="143b9-127">The create or update ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeCreateOrUpdateParameters) As Task(Of ComputeTypeCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-128">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-128">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-129">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-129">Required.</span></span> <span data-ttu-id="143b9-130">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-130">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-131">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-131">Required.</span></span> <span data-ttu-id="143b9-132">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-132">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="143b9-133">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-133">Required.</span></span> <span data-ttu-id="143b9-134">作成または ComputeType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="143b9-134">The parameters required to create or update an ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-135">作成または、ComputeType を更新します。</span><span class="sxs-lookup"><span data-stu-id="143b9-135">Create or update an ComputeType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-136">作成または更新 ComputeType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="143b9-136">The create or update ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName, Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String, parameters As ComputeTypeCreateOrUpdateWithRawJsonContentParameters) As ComputeTypeCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, computeTypeName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-137">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-137">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-138">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-138">Required.</span></span> <span data-ttu-id="143b9-139">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-139">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-140">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-140">Required.</span></span> <span data-ttu-id="143b9-141">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-141">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="143b9-142">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-142">Required.</span></span> <span data-ttu-id="143b9-143">ComputeType 名前です。</span><span class="sxs-lookup"><span data-stu-id="143b9-143">An ComputeType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="143b9-144">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-144">Required.</span></span> <span data-ttu-id="143b9-145">作成または ComputeType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="143b9-145">The parameters required to create or update an ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-146">作成または、ComputeType を更新します。</span><span class="sxs-lookup"><span data-stu-id="143b9-146">Create or update an ComputeType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-147">作成または更新 ComputeType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="143b9-147">The create or update ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName, Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String, parameters As ComputeTypeCreateOrUpdateWithRawJsonContentParameters) As Task(Of ComputeTypeCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, computeTypeName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-148">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-148">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-149">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-149">Required.</span></span> <span data-ttu-id="143b9-150">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-150">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-151">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-151">Required.</span></span> <span data-ttu-id="143b9-152">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-152">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="143b9-153">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-153">Required.</span></span> <span data-ttu-id="143b9-154">ComputeType 名前です。</span><span class="sxs-lookup"><span data-stu-id="143b9-154">An ComputeType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="143b9-155">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-155">Required.</span></span> <span data-ttu-id="143b9-156">作成または ComputeType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="143b9-156">The parameters required to create or update an ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-157">作成または、ComputeType を更新します。</span><span class="sxs-lookup"><span data-stu-id="143b9-157">Create or update an ComputeType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-158">作成または更新 ComputeType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="143b9-158">The create or update ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, computeTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-159">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-159">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-160">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-160">Required.</span></span> <span data-ttu-id="143b9-161">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-162">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-162">Required.</span></span> <span data-ttu-id="143b9-163">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-163">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="143b9-164">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-164">Required.</span></span> <span data-ttu-id="143b9-165">ComputeType の名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-165">The name of the computeType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-166">ComputeType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="143b9-166">Delete an ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-167">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="143b9-167">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, string computeTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, computeTypeName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, computeTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="computeTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-168">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-168">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-169">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-169">Required.</span></span> <span data-ttu-id="143b9-170">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-171">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-171">Required.</span></span> <span data-ttu-id="143b9-172">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-172">The name of the data factory.</span></span>
            </param>
        <param name="computeTypeName">
            <span data-ttu-id="143b9-173">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-173">Required.</span></span> <span data-ttu-id="143b9-174">ComputeType の名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-174">The name of the computeType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-175">ComputeType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="143b9-175">Delete an ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-176">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="143b9-176">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetResponse Get (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetResponse Get(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeGetParameters) As ComputeTypeGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetResponse" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-177">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-177">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-178">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-178">Required.</span></span> <span data-ttu-id="143b9-179">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-180">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-180">Required.</span></span> <span data-ttu-id="143b9-181">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-181">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="143b9-182">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-182">Required.</span></span> <span data-ttu-id="143b9-183">ComputeType 定義を取得する方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="143b9-183">Parameters specifying how to get an ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-184">ComputeType インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="143b9-184">Gets an ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-185">ComputeType の取得操作の応答。</span><span class="sxs-lookup"><span data-stu-id="143b9-185">The Get ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeGetParameters) As Task(Of ComputeTypeGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeGetParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-186">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-186">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-187">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-187">Required.</span></span> <span data-ttu-id="143b9-188">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-188">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-189">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-189">Required.</span></span> <span data-ttu-id="143b9-190">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-190">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="143b9-191">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-191">Required.</span></span> <span data-ttu-id="143b9-192">ComputeType 定義を取得する方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="143b9-192">Parameters specifying how to get an ComputeType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-193">ComputeType インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="143b9-193">Gets an ComputeType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-194">ComputeType の取得操作の応答。</span><span class="sxs-lookup"><span data-stu-id="143b9-194">The Get ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse List (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse List(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeListParameters) As ComputeTypeListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.List (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-195">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-195">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-196">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-196">Required.</span></span> <span data-ttu-id="143b9-197">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-197">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-198">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-198">Required.</span></span> <span data-ttu-id="143b9-199">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-199">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="143b9-200">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-200">Required.</span></span> <span data-ttu-id="143b9-201">ComputeType 定義の一覧を返す方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="143b9-201">Parameters specifying how to return a list of ComputeType definitions.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-202">次のページへのリンクを持つ ComputeType インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="143b9-202">Gets the first page of ComputeType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-203">リスト ComputeType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="143b9-203">The List ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IComputeTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ComputeTypeListParameters) As Task(Of ComputeTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-204">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-204">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="143b9-205">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-205">Required.</span></span> <span data-ttu-id="143b9-206">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="143b9-206">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="143b9-207">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-207">Required.</span></span> <span data-ttu-id="143b9-208">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="143b9-208">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="143b9-209">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-209">Required.</span></span> <span data-ttu-id="143b9-210">ComputeType 定義の一覧を返す方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="143b9-210">Parameters specifying how to return a list of ComputeType definitions.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-211">次のページへのリンクを持つ ComputeType インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="143b9-211">Gets the first page of ComputeType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-212">リスト ComputeType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="143b9-212">The List ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse ListNext (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse ListNext(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IComputeTypeOperations, nextLink As String) As ComputeTypeListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-213">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-213">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="143b9-214">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-214">Required.</span></span> <span data-ttu-id="143b9-215">次の Computetype ページの url です。</span><span class="sxs-lookup"><span data-stu-id="143b9-215">The url to the next ComputeTypes page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-216">次のページへのリンクを持つ ComputeType インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="143b9-216">Gets the next page of ComputeType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-217">リスト ComputeType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="143b9-217">The List ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.IComputeTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.IComputeTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IComputeTypeOperations, nextLink As String) As Task(Of ComputeTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.IComputeTypeOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ComputeTypeOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ComputeTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IComputeTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="143b9-218">Microsoft.Azure.Management.DataFactories.IComputeTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="143b9-218">Reference to the Microsoft.Azure.Management.DataFactories.IComputeTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="143b9-219">必須。</span><span class="sxs-lookup"><span data-stu-id="143b9-219">Required.</span></span> <span data-ttu-id="143b9-220">次の Computetype ページの url です。</span><span class="sxs-lookup"><span data-stu-id="143b9-220">The url to the next ComputeTypes page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="143b9-221">次のページへのリンクを持つ ComputeType インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="143b9-221">Gets the next page of ComputeType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="143b9-222">リスト ComputeType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="143b9-222">The List ComputeType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>