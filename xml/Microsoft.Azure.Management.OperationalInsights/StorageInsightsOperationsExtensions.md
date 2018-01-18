<Type Name="StorageInsightsOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageInsightsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageInsightsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageInsightsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageInsightsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="78c0b-101">StorageInsightsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="78c0b-101">Extension methods for StorageInsightsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IStorageInsightsOperations, resourceGroupName As String, workspaceName As String, storageInsightName As String, parameters As StorageInsight) As StorageInsight" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight -&gt; Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, storageInsightName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="78c0b-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="78c0b-103">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="78c0b-103">The name of the resource group to get.</span></span> <span data-ttu-id="78c0b-104">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-104">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="78c0b-105">StorageInsightsConfigs リソースを格納するログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="78c0b-105">Log Analytics Workspace name that will contain the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="78c0b-106">StorageInsightsConfigs リソースの名前</span><span class="sxs-lookup"><span data-stu-id="78c0b-106">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="78c0b-107">作成または記憶域の洞察を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-107">The parameters required to create or update a storage insight.</span></span>
            </param>
        <summary>
            <span data-ttu-id="78c0b-108">作成または記憶域の洞察を更新します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-108">Create or update a storage insight.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, storageInsightName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="78c0b-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="78c0b-110">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="78c0b-110">The name of the resource group to get.</span></span> <span data-ttu-id="78c0b-111">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-111">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="78c0b-112">StorageInsightsConfigs リソースを格納するログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="78c0b-112">Log Analytics Workspace name that will contain the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="78c0b-113">StorageInsightsConfigs リソースの名前</span><span class="sxs-lookup"><span data-stu-id="78c0b-113">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="78c0b-114">作成または記憶域の洞察を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-114">The parameters required to create or update a storage insight.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="78c0b-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="78c0b-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="78c0b-116">作成または記憶域の洞察を更新します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-116">Create or update a storage insight.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStorageInsightsOperations, resourceGroupName As String, workspaceName As String, storageInsightName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.Delete (operations, resourceGroupName, workspaceName, storageInsightName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="78c0b-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="78c0b-118">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="78c0b-118">The name of the resource group to get.</span></span> <span data-ttu-id="78c0b-119">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-119">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="78c0b-120">ログ分析ワークスペース名 storageInsightsConfigs リソースを含む</span><span class="sxs-lookup"><span data-stu-id="78c0b-120">Log Analytics Workspace name that contains the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="78c0b-121">StorageInsightsConfigs リソースの名前</span><span class="sxs-lookup"><span data-stu-id="78c0b-121">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="78c0b-122">StorageInsightsConfigs リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-122">Deletes a storageInsightsConfigs resource</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, storageInsightName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="78c0b-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="78c0b-124">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="78c0b-124">The name of the resource group to get.</span></span> <span data-ttu-id="78c0b-125">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-125">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="78c0b-126">ログ分析ワークスペース名 storageInsightsConfigs リソースを含む</span><span class="sxs-lookup"><span data-stu-id="78c0b-126">Log Analytics Workspace name that contains the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="78c0b-127">StorageInsightsConfigs リソースの名前</span><span class="sxs-lookup"><span data-stu-id="78c0b-127">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="78c0b-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="78c0b-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="78c0b-129">StorageInsightsConfigs リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-129">Deletes a storageInsightsConfigs resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight Get (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight Get(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IStorageInsightsOperations, resourceGroupName As String, workspaceName As String, storageInsightName As String) As StorageInsight" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.Get (operations, resourceGroupName, workspaceName, storageInsightName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="78c0b-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="78c0b-131">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="78c0b-131">The name of the resource group to get.</span></span> <span data-ttu-id="78c0b-132">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-132">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="78c0b-133">ログ分析ワークスペース名 storageInsightsConfigs リソースを含む</span><span class="sxs-lookup"><span data-stu-id="78c0b-133">Log Analytics Workspace name that contains the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="78c0b-134">StorageInsightsConfigs リソースの名前</span><span class="sxs-lookup"><span data-stu-id="78c0b-134">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="78c0b-135">ストレージ インサイト インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-135">Gets a storage insight instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, string storageInsightName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, storageInsightName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="78c0b-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="78c0b-137">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="78c0b-137">The name of the resource group to get.</span></span> <span data-ttu-id="78c0b-138">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-138">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="78c0b-139">ログ分析ワークスペース名 storageInsightsConfigs リソースを含む</span><span class="sxs-lookup"><span data-stu-id="78c0b-139">Log Analytics Workspace name that contains the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="78c0b-140">StorageInsightsConfigs リソースの名前</span><span class="sxs-lookup"><span data-stu-id="78c0b-140">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="78c0b-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="78c0b-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="78c0b-142">ストレージ インサイト インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-142">Gets a storage insight instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspace">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; ListByWorkspace (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; ListByWorkspace(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspace(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspace (operations As IStorageInsightsOperations, resourceGroupName As String, workspaceName As String) As IPage(Of StorageInsight)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspace : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspace (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="78c0b-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="78c0b-144">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="78c0b-144">The name of the resource group to get.</span></span> <span data-ttu-id="78c0b-145">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-145">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="78c0b-146">StorageInsightsConfigs リソースを格納するログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="78c0b-146">Log Analytics Workspace name that will contain the storageInsightsConfigs resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="78c0b-147">ワークスペース内で記憶域 insight インスタンスが一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-147">Lists the storage insight instances within a workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; ListByWorkspaceAsync (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; ListByWorkspaceAsync(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceAsync(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceAsync : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions/&lt;ListByWorkspaceAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="78c0b-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="78c0b-149">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="78c0b-149">The name of the resource group to get.</span></span> <span data-ttu-id="78c0b-150">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-150">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="78c0b-151">StorageInsightsConfigs リソースを格納するログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="78c0b-151">Log Analytics Workspace name that will contain the storageInsightsConfigs resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="78c0b-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="78c0b-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="78c0b-153">ワークスペース内で記憶域 insight インスタンスが一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-153">Lists the storage insight instances within a workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; ListByWorkspaceNext (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt; ListByWorkspaceNext(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceNext(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspaceNext (operations As IStorageInsightsOperations, nextPageLink As String) As IPage(Of StorageInsight)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceNext : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="78c0b-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-154">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="78c0b-155">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="78c0b-155">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="78c0b-156">ワークスペース内で記憶域 insight インスタンスが一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-156">Lists the storage insight instances within a workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; ListByWorkspaceNextAsync (this Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; ListByWorkspaceNextAsync(class Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceNextAsync(Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceNextAsync : Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions.ListByWorkspaceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.StorageInsightsOperationsExtensions/&lt;ListByWorkspaceNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="78c0b-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="78c0b-157">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="78c0b-158">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="78c0b-158">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="78c0b-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="78c0b-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="78c0b-160">ワークスペース内で記憶域 insight インスタンスが一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="78c0b-160">Lists the storage insight instances within a workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>