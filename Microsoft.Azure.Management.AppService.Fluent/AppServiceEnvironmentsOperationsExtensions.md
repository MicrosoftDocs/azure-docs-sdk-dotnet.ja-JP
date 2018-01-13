<Type Name="AppServiceEnvironmentsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServiceEnvironmentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServiceEnvironmentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServiceEnvironmentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3862f-101">AppServiceEnvironmentsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="3862f-101">Extension methods for AppServiceEnvironmentsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, name, hostingEnvironmentEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__36))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-104">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-104">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="3862f-105">App Service 環境の構成の詳細。</span><span class="sxs-lookup"><span data-stu-id="3862f-105">Configuration details of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-107">作成または App Service 環境を更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-107">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-108">作成または App Service 環境を更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-108">Create or update an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateMultiRolePoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateMultiRolePoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateMultiRolePoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateMultiRolePoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateMultiRolePoolAsync (operations, resourceGroupName, name, multiRolePoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateMultiRolePoolAsync&gt;d__38))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-110">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-111">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-111">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="3862f-112">マルチロール プールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="3862f-112">Properties of the multi-role pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-114">作成またはマルチロール プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-114">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-115">作成またはマルチロール プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-115">Create or update a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateWorkerPoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; BeginCreateOrUpdateWorkerPoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateWorkerPoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWorkerPoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginCreateOrUpdateWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginCreateOrUpdateWorkerPoolAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-117">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-117">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-118">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-118">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3862f-119">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-119">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="3862f-120">ワーカー プールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="3862f-120">Properties of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-122">作成またはワーカー プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-122">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-123">作成またはワーカー プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-123">Create or update a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, name, forceDelete, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-125">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-125">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-126">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-126">Name of the App Service Environment.</span></span>
            </param>
        <param name="forceDelete">
            <span data-ttu-id="3862f-127">指定&lt;コード&gt;true&lt;/code&gt;を App Service 環境には、リソースが含まれている場合でも強制的に削除します。</span><span class="sxs-lookup"><span data-stu-id="3862f-127">Specify &lt;code&gt;true&lt;/code&gt; to force the deletion even if the App Service Environment contains resources.</span></span> <span data-ttu-id="3862f-128">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="3862f-128">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-130">App Service 環境を削除します。</span><span class="sxs-lookup"><span data-stu-id="3862f-130">Delete an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-131">App Service 環境を削除します。</span><span class="sxs-lookup"><span data-stu-id="3862f-131">Delete an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginResumeAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-133">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-133">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-134">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-134">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-136">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="3862f-136">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-137">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="3862f-137">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginResumeNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResumeNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginResumeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginResumeNextAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-138">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-139">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-139">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-141">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="3862f-141">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-142">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="3862f-142">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSuspendAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginSuspendAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-144">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-145">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-145">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-147">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="3862f-147">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-148">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="3862f-148">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; BeginSuspendNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSuspendNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.BeginSuspendNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;BeginSuspendNextAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-149">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-150">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-150">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-152">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="3862f-152">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-153">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="3862f-153">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner hostingEnvironmentEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, hostingEnvironmentEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-155">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-155">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-156">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-156">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="3862f-157">App Service 環境の構成の詳細。</span><span class="sxs-lookup"><span data-stu-id="3862f-157">Configuration details of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-159">作成または App Service 環境を更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-159">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-160">作成または App Service 環境を更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-160">Create or update an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateMultiRolePoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateMultiRolePoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner multiRolePoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateMultiRolePoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateMultiRolePoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateMultiRolePoolAsync (operations, resourceGroupName, name, multiRolePoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateMultiRolePoolAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-162">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-162">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-163">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-163">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="3862f-164">マルチロール プールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="3862f-164">Properties of the multi-role pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-166">作成またはマルチロール プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-166">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-167">作成またはマルチロール プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-167">Create or update a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateWorkerPoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; CreateOrUpdateWorkerPoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner workerPoolEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateWorkerPoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWorkerPoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.CreateOrUpdateWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, workerPoolEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;CreateOrUpdateWorkerPoolAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-169">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-169">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-170">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-170">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3862f-171">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-171">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="3862f-172">ワーカー プールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="3862f-172">Properties of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-174">作成またはワーカー プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-174">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-175">作成またはワーカー プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="3862f-175">Create or update a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, forceDelete, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-177">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-177">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-178">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-178">Name of the App Service Environment.</span></span>
            </param>
        <param name="forceDelete">
            <span data-ttu-id="3862f-179">指定&lt;コード&gt;true&lt;/code&gt;を App Service 環境には、リソースが含まれている場合でも強制的に削除します。</span><span class="sxs-lookup"><span data-stu-id="3862f-179">Specify &lt;code&gt;true&lt;/code&gt; to force the deletion even if the App Service Environment contains resources.</span></span> <span data-ttu-id="3862f-180">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="3862f-180">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-182">App Service 環境を削除します。</span><span class="sxs-lookup"><span data-stu-id="3862f-182">Delete an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-183">App Service 環境を削除します。</span><span class="sxs-lookup"><span data-stu-id="3862f-183">Delete an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-184">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-185">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-185">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-186">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-186">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-188">App Service 環境のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-188">Get the properties of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-189">App Service 環境のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-189">Get the properties of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDiagnosticsItemAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt; GetDiagnosticsItemAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string diagnosticsName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt; GetDiagnosticsItemAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string diagnosticsName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetDiagnosticsItemAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDiagnosticsItemAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetDiagnosticsItemAsync (operations, resourceGroupName, name, diagnosticsName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetDiagnosticsItemAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="diagnosticsName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-191">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-191">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-192">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-192">Name of the App Service Environment.</span></span>
            </param>
        <param name="diagnosticsName">
            <span data-ttu-id="3862f-193">診断の項目の名前。</span><span class="sxs-lookup"><span data-stu-id="3862f-193">Name of the diagnostics item.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-195">App Service 環境の診断の項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-195">Get a diagnostics item for an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-196">App Service 環境の診断の項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-196">Get a diagnostics item for an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMultiRolePoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetMultiRolePoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetMultiRolePoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetMultiRolePoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMultiRolePoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetMultiRolePoolAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetMultiRolePoolAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-198">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-198">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-199">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-199">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-201">マルチロール プールのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-201">Get properties of a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-202">マルチロール プールのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-202">Get properties of a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWorkerPoolAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetWorkerPoolAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt; GetWorkerPoolAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetWorkerPoolAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetWorkerPoolAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.GetWorkerPoolAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;GetWorkerPoolAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-203">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-203">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-204">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-204">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-205">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-205">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3862f-206">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-206">Name of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-208">ワーカー プールのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-208">Get properties of a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-209">ワーカー プールのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-209">Get properties of a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAppServicePlansAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListAppServicePlansAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-211">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-211">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-212">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-212">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-214">App Service Environment ですべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-214">Get all App Service plans in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-215">App Service Environment ですべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-215">Get all App Service plans in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAppServicePlansNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAppServicePlansNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAppServicePlansNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListAppServicePlansNextAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-216">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-216">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-217">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-217">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-219">App Service Environment ですべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-219">Get all App Service plans in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-220">App Service Environment ですべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-220">Get all App Service plans in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-221">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-222">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-223">App Service 環境のすべてのサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-223">Get all App Service Environments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-224">App Service 環境のすべてのサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-224">Get all App Service Environments for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-225">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-226">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-226">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-228">リソース グループ内のすべての App Service 環境を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-228">Get all App Service Environments in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-229">リソース グループ内のすべての App Service 環境を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-229">Get all App Service Environments in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-230">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-230">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-231">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-231">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-232">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-232">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-233">リソース グループ内のすべての App Service 環境を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-233">Get all App Service Environments in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-234">リソース グループ内のすべての App Service 環境を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-234">Get all App Service Environments in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapacitiesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListCapacitiesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-235">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-235">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-236">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-236">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-237">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-237">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-238">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-239">App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-239">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-240">App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-240">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt; ListCapacitiesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapacitiesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListCapacitiesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListCapacitiesNextAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-241">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-241">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-242">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-242">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-243">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-243">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-244">App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-244">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-245">App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-245">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDiagnosticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt; ListDiagnosticsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt; ListDiagnosticsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListDiagnosticsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDiagnosticsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListDiagnosticsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListDiagnosticsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentDiagnosticsInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-246">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-246">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-247">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-247">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-248">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-248">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-250">App Service 環境の診断情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-250">Get diagnostic information for an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-251">App Service 環境の診断情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-251">Get diagnostic information for an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt; ListMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt; ListMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricDefinitionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricDefinitionsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.MetricDefinitionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-252">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-252">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-253">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-253">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-254">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-254">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-256">App Service 環境のグローバルのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-256">Get global metric definitions of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-257">App Service 環境のグローバルのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-257">Get global metric definitions of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, name, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricsAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-258">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-258">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-259">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-259">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-260">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-260">Name of the App Service Environment.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="3862f-261">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="3862f-261">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="3862f-262">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="3862f-262">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="3862f-263">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="3862f-263">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="3862f-264">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="3862f-264">Filter conforms to odata syntax.</span></span> <span data-ttu-id="3862f-265">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="3862f-265">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-266">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-266">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-267">App Service 環境のグローバルのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-267">Get global metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-268">App Service 環境のグローバルのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-268">Get global metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMetricsNextAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-269">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-269">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-270">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-270">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-271">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-272">App Service 環境のグローバルのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-272">Get global metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-273">App Service 環境のグローバルのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-273">Get global metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricDefinitionsAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRoleMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricDefinitionsNextAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string startTime = null, string endTime = null, string timeGrain = null, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string startTime, string endTime, string timeGrain, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsAsync (operations, resourceGroupName, name, startTime, endTime, timeGrain, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-274">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-274">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-275">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-275">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-276">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-276">Name of the App Service Environment.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="3862f-277">メトリックのクエリの時間を開始しています。</span><span class="sxs-lookup"><span data-stu-id="3862f-277">Beginning time of the metrics query.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="3862f-278">メトリックのクエリの終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="3862f-278">End time of the metrics query.</span></span>
            </param>
        <param name="timeGrain">
            <span data-ttu-id="3862f-279">メトリックのクエリの時間粒度。</span><span class="sxs-lookup"><span data-stu-id="3862f-279">Time granularity of the metrics query.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="3862f-280">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="3862f-280">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="3862f-281">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="3862f-281">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="3862f-282">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="3862f-282">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="3862f-283">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="3862f-283">Filter conforms to odata syntax.</span></span> <span data-ttu-id="3862f-284">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="3862f-284">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-285">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-285">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-286">App Service 環境のマルチロール プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-286">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-287">App Service 環境のマルチロール プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-287">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRoleMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleMetricsNextAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-288">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-288">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-289">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-289">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-290">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-290">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-291">App Service 環境のマルチロール プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-291">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-292">App Service 環境のマルチロール プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-292">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsAsync (operations, resourceGroupName, name, instance, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricDefinitionsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="instance">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricDefinitionsNextAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, Nullable&lt;bool&gt; details = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string instance, valuetype System.Nullable`1&lt;bool&gt; details, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsAsync (operations, resourceGroupName, name, instance, details, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-293">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-293">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-294">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-294">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-295">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-295">Name of the App Service Environment.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="3862f-296">マルチロール プール内のインスタンスの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-296">Name of the instance in the multi-role pool.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="3862f-297">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="3862f-297">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="3862f-298">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="3862f-298">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-299">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-300">App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-300">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-301">App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-301">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMultiRolePoolInstanceMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolInstanceMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolInstanceMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolInstanceMetricsNextAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-302">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-302">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-303">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-303">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-304">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-304">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-305">App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-305">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-306">App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-306">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-307">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-307">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-308">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-308">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-309">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-309">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-310">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-310">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-311">マルチロールすべてのプールを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-311">Get all multi-role pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-312">マルチロールすべてのプールを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-312">Get all multi-role pools.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolSkusAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolSkusAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-313">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-313">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-314">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-314">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-315">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-315">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-316">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-317">マルチロール プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-317">Get available SKUs for scaling a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-318">マルチロール プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-318">Get available SKUs for scaling a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListMultiRolePoolSkusNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolSkusNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolSkusNextAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-319">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-319">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-320">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-320">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-321">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-322">マルチロール プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-322">Get available SKUs for scaling a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-323">マルチロール プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-323">Get available SKUs for scaling a multi-role pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListMultiRolePoolsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRolePoolsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRolePoolsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRolePoolsNextAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-324">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-324">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-325">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-325">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-326">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-327">マルチロールすべてのプールを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-327">Get all multi-role pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-328">マルチロールすべてのプールを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-328">Get all multi-role pools.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleUsagesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleUsagesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListMultiRoleUsagesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMultiRoleUsagesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListMultiRoleUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListMultiRoleUsagesNextAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListNextAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-329">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-329">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-330">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-330">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-331">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-331">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-332">App Service 環境のすべてのサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-332">Get all App Service Environments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-333">App Service 環境のすべてのサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-333">Get all App Service Environments for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt; ListOperationsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt; ListOperationsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListOperationsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOperationsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListOperationsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListOperationsAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.OperationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-334">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-334">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-335">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-335">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-336">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-336">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-337">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-337">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-338">App Service 環境の現在実行されているすべての操作を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="3862f-338">List all currently running operations on the App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-339">App Service 環境の現在実行されているすべての操作を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="3862f-339">List all currently running operations on the App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, name, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListUsagesAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-340">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-340">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-341">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-341">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-342">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-342">Name of the App Service Environment.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="3862f-343">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="3862f-343">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="3862f-344">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="3862f-344">Filter conforms to odata syntax.</span></span> <span data-ttu-id="3862f-345">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="3862f-345">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-346">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-346">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-347">App Service 環境のグローバルの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-347">Get global usage metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-348">App Service 環境のグローバルの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-348">Get global usage metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListUsagesNextAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-349">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-349">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-350">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-350">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-351">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-351">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-352">App Service 環境のグローバルの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-352">Get global usage metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-353">App Service 環境のグローバルの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-353">Get global usage metrics of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVipsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt; ListVipsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt; ListVipsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListVipsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVipsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListVipsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListVipsAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-354">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-354">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-355">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-355">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-356">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-356">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-357">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-357">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-358">App Service 環境に割り当てる IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-358">Get IP addresses assigned to an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-359">App Service 環境に割り当てる IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-359">Get IP addresses assigned to an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string propertiesToInclude = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string propertiesToInclude, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsAsync (operations, resourceGroupName, name, propertiesToInclude, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebAppsAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="propertiesToInclude" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-360">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-360">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-361">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-361">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-362">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-362">Name of the App Service Environment.</span></span>
            </param>
        <param name="propertiesToInclude">
            <span data-ttu-id="3862f-363">コンマ区切りリストに含めるアプリのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="3862f-363">Comma separated list of app properties to include.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-364">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-364">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-365">App Service Environment ですべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-365">Get all apps in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-366">App Service Environment ですべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-366">Get all apps in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebAppsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebAppsNextAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-367">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-367">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-368">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-368">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-369">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-369">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-370">App Service Environment ですべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-370">Get all apps in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-371">App Service Environment ですべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-371">Get all apps in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricDefinitionsAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="workerPoolName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWebWorkerMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricDefinitionsNextAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsAsync (operations, resourceGroupName, name, workerPoolName, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricsAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-372">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-372">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-373">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-373">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-374">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-374">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3862f-375">ワーカー プールの名前</span><span class="sxs-lookup"><span data-stu-id="3862f-375">Name of worker pool</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="3862f-376">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="3862f-376">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="3862f-377">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="3862f-377">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="3862f-378">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="3862f-378">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="3862f-379">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="3862f-379">Filter conforms to odata syntax.</span></span> <span data-ttu-id="3862f-380">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="3862f-380">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-381">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-381">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-382">AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-382">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-383">AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-383">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWebWorkerMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerMetricsNextAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-384">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-384">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-385">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-385">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-386">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-386">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-387">AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-387">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-388">AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-388">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerUsagesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerUsagesAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="workerPoolName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt; ListWebWorkerUsagesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebWorkerUsagesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWebWorkerUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWebWorkerUsagesNextAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Usage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricDefinitionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsAsync (operations, resourceGroupName, name, workerPoolName, instance, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricDefinitionsAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="name">To be added.</param>
        <param name="workerPoolName">To be added.</param>
        <param name="instance">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricDefinitionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricDefinitionsNextAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, string instance, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsAsync (operations, resourceGroupName, name, workerPoolName, instance, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricsAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-389">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-389">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-390">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-390">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-391">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-391">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3862f-392">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-392">Name of the worker pool.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="3862f-393">ワーカー プールのインスタンスの名前。</span><span class="sxs-lookup"><span data-stu-id="3862f-393">Name of the instance in the worker pool.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="3862f-394">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="3862f-394">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="3862f-395">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="3862f-395">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="3862f-396">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="3862f-396">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="3862f-397">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="3862f-397">Filter conforms to odata syntax.</span></span> <span data-ttu-id="3862f-398">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="3862f-398">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-399">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-399">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-400">App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-400">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-401">App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-401">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListWorkerPoolInstanceMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolInstanceMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolInstanceMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolInstanceMetricsNextAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-402">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-402">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-403">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-403">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-404">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-404">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-405">App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-405">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-406">App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-406">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-407">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-407">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-408">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-408">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-409">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-409">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-410">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-410">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-411">App Service 環境のすべてのワーカー プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-411">Get all worker pools of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-412">App Service 環境のすべてのワーカー プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-412">Get all worker pools of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, string workerPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolSkusAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusAsync (operations, resourceGroupName, name, workerPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolSkusAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-413">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-413">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-414">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-414">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-415">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-415">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="3862f-416">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-416">Name of the worker pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-417">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-417">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-418">ワーカー プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-418">Get available SKUs for scaling a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-419">ワーカー プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-419">Get available SKUs for scaling a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt; ListWorkerPoolSkusNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolSkusNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolSkusNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolSkusNextAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SkuInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-420">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-420">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-421">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-421">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-422">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-422">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-423">ワーカー プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-423">Get available SKUs for scaling a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-424">ワーカー プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-424">Get available SKUs for scaling a worker pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt; ListWorkerPoolsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWorkerPoolsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ListWorkerPoolsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ListWorkerPoolsNextAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPoolResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-425">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-425">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-426">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-426">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-427">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-427">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-428">App Service 環境のすべてのワーカー プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-428">Get all worker pools of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-429">App Service 環境のすべてのワーカー プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="3862f-429">Get all worker pools of an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RebootAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RebootAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.RebootAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebootAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.RebootAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;RebootAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-430">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-430">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-431">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-431">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-432">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-432">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-433">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-433">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-434">App Service 環境のすべてのマシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="3862f-434">Reboot all machines in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-435">App Service 環境のすべてのマシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="3862f-435">Reboot all machines in an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ResumeAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-436">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-436">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-437">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-437">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-438">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-438">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-439">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-439">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-440">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="3862f-440">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-441">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="3862f-441">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ResumeNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResumeNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.ResumeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;ResumeNextAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-442">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-442">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-443">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-443">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-444">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-444">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-445">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="3862f-445">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-446">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="3862f-446">Resume an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuspendAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;SuspendAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-447">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-447">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3862f-448">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-448">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="3862f-449">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="3862f-449">Name of the App Service Environment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-450">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-450">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-451">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="3862f-451">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-452">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="3862f-452">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; SuspendNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuspendNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions.SuspendNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceEnvironmentsOperationsExtensions/&lt;SuspendNextAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceEnvironmentsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3862f-453">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3862f-453">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3862f-454">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3862f-454">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3862f-455">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3862f-455">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3862f-456">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="3862f-456">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3862f-457">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="3862f-457">Suspend an App Service Environment.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>