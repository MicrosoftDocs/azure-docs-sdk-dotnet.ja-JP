<Type Name="ActivityTypeOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActivityTypeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActivityTypeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActivityTypeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ActivityTypeOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, activityTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-101">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-101">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-102">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-102">Required.</span></span> <span data-ttu-id="44c0b-103">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-104">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-104">Required.</span></span> <span data-ttu-id="44c0b-105">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-105">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="44c0b-106">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-106">Required.</span></span> <span data-ttu-id="44c0b-107">ActivityType の名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-107">The name of the activityType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-108">ActivityType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-108">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-109">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-109">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, activityTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-110">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-110">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-111">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-111">Required.</span></span> <span data-ttu-id="44c0b-112">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-113">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-113">Required.</span></span> <span data-ttu-id="44c0b-114">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-114">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="44c0b-115">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-115">Required.</span></span> <span data-ttu-id="44c0b-116">ActivityType の名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-116">The name of the activityType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-117">ActivityType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-117">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-118">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-118">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeCreateOrUpdateParameters) As ActivityTypeCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-119">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-119">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-120">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-120">Required.</span></span> <span data-ttu-id="44c0b-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-122">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-122">Required.</span></span> <span data-ttu-id="44c0b-123">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-123">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="44c0b-124">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-124">Required.</span></span> <span data-ttu-id="44c0b-125">作成または ActivityType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="44c0b-125">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-126">作成または、ActivityType を更新します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-126">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-127">作成または更新 ActivityType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="44c0b-127">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeCreateOrUpdateParameters) As Task(Of ActivityTypeCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-128">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-128">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-129">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-129">Required.</span></span> <span data-ttu-id="44c0b-130">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-130">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-131">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-131">Required.</span></span> <span data-ttu-id="44c0b-132">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-132">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="44c0b-133">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-133">Required.</span></span> <span data-ttu-id="44c0b-134">作成または ActivityType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="44c0b-134">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-135">作成または、ActivityType を更新します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-135">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-136">作成または更新 ActivityType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="44c0b-136">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String, parameters As ActivityTypeCreateOrUpdateWithRawJsonContentParameters) As ActivityTypeCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, activityTypeName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-137">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-137">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-138">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-138">Required.</span></span> <span data-ttu-id="44c0b-139">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-139">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-140">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-140">Required.</span></span> <span data-ttu-id="44c0b-141">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-141">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="44c0b-142">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-142">Required.</span></span> <span data-ttu-id="44c0b-143">ActivityType の名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-143">An ActivityType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="44c0b-144">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-144">Required.</span></span> <span data-ttu-id="44c0b-145">作成または ActivityType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="44c0b-145">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-146">作成または、ActivityType を更新します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-146">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-147">作成または更新 ActivityType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="44c0b-147">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String, parameters As ActivityTypeCreateOrUpdateWithRawJsonContentParameters) As Task(Of ActivityTypeCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, activityTypeName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-148">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-148">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-149">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-149">Required.</span></span> <span data-ttu-id="44c0b-150">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-150">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-151">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-151">Required.</span></span> <span data-ttu-id="44c0b-152">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-152">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="44c0b-153">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-153">Required.</span></span> <span data-ttu-id="44c0b-154">ActivityType の名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-154">An ActivityType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="44c0b-155">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-155">Required.</span></span> <span data-ttu-id="44c0b-156">作成または ActivityType 定義を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="44c0b-156">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-157">作成または、ActivityType を更新します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-157">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-158">作成または更新 ActivityType 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="44c0b-158">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, activityTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-159">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-159">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-160">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-160">Required.</span></span> <span data-ttu-id="44c0b-161">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-162">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-162">Required.</span></span> <span data-ttu-id="44c0b-163">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-163">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="44c0b-164">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-164">Required.</span></span> <span data-ttu-id="44c0b-165">ActivityType の名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-165">The name of the activityType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-166">ActivityType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-166">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-167">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-167">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, string activityTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, activityTypeName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, activityTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-168">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-168">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-169">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-169">Required.</span></span> <span data-ttu-id="44c0b-170">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-171">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-171">Required.</span></span> <span data-ttu-id="44c0b-172">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-172">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="44c0b-173">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-173">Required.</span></span> <span data-ttu-id="44c0b-174">ActivityType の名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-174">The name of the activityType.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-175">ActivityType インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-175">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-176">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-176">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse Get (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse Get(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeGetParameters) As ActivityTypeGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-177">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-177">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-178">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-178">Required.</span></span> <span data-ttu-id="44c0b-179">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-180">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-180">Required.</span></span> <span data-ttu-id="44c0b-181">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-181">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="44c0b-182">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-182">Required.</span></span> <span data-ttu-id="44c0b-183">ActivityType 定義を取得する方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="44c0b-183">Parameters specifying how to get an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-184">ActivityType インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-184">Gets an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-185">ActivityType の取得操作の応答。</span><span class="sxs-lookup"><span data-stu-id="44c0b-185">The Get ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeGetParameters) As Task(Of ActivityTypeGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-186">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-186">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-187">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-187">Required.</span></span> <span data-ttu-id="44c0b-188">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-188">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-189">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-189">Required.</span></span> <span data-ttu-id="44c0b-190">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-190">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="44c0b-191">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-191">Required.</span></span> <span data-ttu-id="44c0b-192">ActivityType 定義を取得する方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="44c0b-192">Parameters specifying how to get an ActivityType definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-193">ActivityType インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-193">Gets an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-194">ActivityType の取得操作の応答。</span><span class="sxs-lookup"><span data-stu-id="44c0b-194">The Get ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse List (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse List(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeListParameters) As ActivityTypeListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.List (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-195">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-195">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-196">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-196">Required.</span></span> <span data-ttu-id="44c0b-197">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-197">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-198">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-198">Required.</span></span> <span data-ttu-id="44c0b-199">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-199">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="44c0b-200">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-200">Required.</span></span> <span data-ttu-id="44c0b-201">ActivityType 定義の一覧を返す方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="44c0b-201">Parameters specifying how to return a list of ActivityType definitions.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-202">次のページへのリンクを持つ ActivityType インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-202">Gets the first page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-203">リスト ActivityType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="44c0b-203">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IActivityTypeOperations, resourceGroupName As String, dataFactoryName As String, parameters As ActivityTypeListParameters) As Task(Of ActivityTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-204">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-204">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="44c0b-205">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-205">Required.</span></span> <span data-ttu-id="44c0b-206">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="44c0b-206">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="44c0b-207">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-207">Required.</span></span> <span data-ttu-id="44c0b-208">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="44c0b-208">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="44c0b-209">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-209">Required.</span></span> <span data-ttu-id="44c0b-210">ActivityType 定義の一覧を返す方法を指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="44c0b-210">Parameters specifying how to return a list of ActivityType definitions.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-211">次のページへのリンクを持つ ActivityType インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-211">Gets the first page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-212">リスト ActivityType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="44c0b-212">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse ListNext (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse ListNext(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IActivityTypeOperations, nextLink As String) As ActivityTypeListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-213">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-213">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="44c0b-214">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-214">Required.</span></span> <span data-ttu-id="44c0b-215">[次へ] の [Activitytype] ページの url です。</span><span class="sxs-lookup"><span data-stu-id="44c0b-215">The url to the next ActivityTypes page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-216">次のページへのリンクを持つ ActivityType インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-216">Gets the next page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-217">リスト ActivityType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="44c0b-217">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.IActivityTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IActivityTypeOperations, nextLink As String) As Task(Of ActivityTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.IActivityTypeOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="44c0b-218">Microsoft.Azure.Management.DataFactories.IActivityTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="44c0b-218">Reference to the Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="44c0b-219">必須。</span><span class="sxs-lookup"><span data-stu-id="44c0b-219">Required.</span></span> <span data-ttu-id="44c0b-220">[次へ] の [Activitytype] ページの url です。</span><span class="sxs-lookup"><span data-stu-id="44c0b-220">The url to the next ActivityTypes page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="44c0b-221">次のページへのリンクを持つ ActivityType インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="44c0b-221">Gets the next page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="44c0b-222">リスト ActivityType 操作の応答。</span><span class="sxs-lookup"><span data-stu-id="44c0b-222">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>