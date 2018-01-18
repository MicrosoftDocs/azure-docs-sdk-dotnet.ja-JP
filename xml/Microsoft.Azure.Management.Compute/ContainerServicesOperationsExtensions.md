<Type Name="ContainerServicesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ContainerServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ContainerServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ContainerServicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6dd0c-101">ContainerServicesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-101">Extension methods for ContainerServicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.ContainerService BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.ContainerService BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String, parameters As ContainerService) As ContainerService" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService -&gt; Microsoft.Azure.Management.Compute.Models.ContainerService" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, containerServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-103">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="6dd0c-104">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-104">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6dd0c-105">作成または更新コンテナー サービス操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-105">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-106">作成するか、コンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-106">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-107">作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-107">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, containerServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-109">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="6dd0c-110">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-110">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6dd0c-111">作成または更新コンテナー サービス操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-111">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6dd0c-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-113">作成するか、コンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-113">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-114">作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-114">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDelete (operations, resourceGroupName, containerServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-116">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-116">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="6dd0c-117">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-117">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-118">指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-118">Deletes the specified container service.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="6dd0c-119">指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-119">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="6dd0c-120">操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-120">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="6dd0c-121">コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-121">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-123">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="6dd0c-124">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-124">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6dd0c-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-126">指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-126">Deletes the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-127">指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-127">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="6dd0c-128">操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-128">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="6dd0c-129">コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-129">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.ContainerService CreateOrUpdate (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.ContainerService CreateOrUpdate(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String, parameters As ContainerService) As ContainerService" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService -&gt; Microsoft.Azure.Management.Compute.Models.ContainerService" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, containerServiceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-131">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-131">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="6dd0c-132">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-132">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6dd0c-133">作成または更新コンテナー サービス操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-133">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-134">作成するか、コンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-134">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-135">作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-135">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Models.ContainerService parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Models.ContainerService parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.ContainerService,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Models.ContainerService * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, containerServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.ContainerService" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-137">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-137">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="6dd0c-138">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-138">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6dd0c-139">作成または更新コンテナー サービス操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-139">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6dd0c-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-141">作成するか、コンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-141">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-142">作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-142">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Delete (operations, resourceGroupName, containerServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-144">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-144">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="6dd0c-145">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-145">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-146">指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-146">Deletes the specified container service.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="6dd0c-147">指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-147">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="6dd0c-148">操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-148">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="6dd0c-149">コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-149">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-151">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-151">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="6dd0c-152">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-152">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6dd0c-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-154">指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-154">Deletes the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-155">指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-155">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="6dd0c-156">操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-156">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="6dd0c-157">コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-157">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.ContainerService Get (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.ContainerService Get(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IContainerServicesOperations, resourceGroupName As String, containerServiceName As String) As ContainerService" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.ContainerService" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.Get (operations, resourceGroupName, containerServiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ContainerService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-159">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="6dd0c-160">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-160">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-161">指定されたコンテナー サービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-161">Gets the properties of the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-162">指定したサブスクリプションとリソース グループで指定されたコンテナー サービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-162">Gets the properties of the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="6dd0c-163">操作は、状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-163">The operation returns the properties including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; GetAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; GetAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.GetAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-165">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-165">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="6dd0c-166">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-166">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6dd0c-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-168">指定されたコンテナー サービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-168">Gets the properties of the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-169">指定したサブスクリプションとリソース グループで指定されたコンテナー サービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-169">Gets the properties of the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="6dd0c-170">操作は、状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-170">The operation returns the properties including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; List (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; List(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.List(Microsoft.Azure.Management.Compute.IContainerServicesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IContainerServicesOperations) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IContainerServicesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-171">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-172">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-172">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-173">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-173">Gets a list of container services in the specified subscription.</span></span> <span data-ttu-id="6dd0c-174">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-174">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-175">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6dd0c-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-177">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-177">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-178">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-178">Gets a list of container services in the specified subscription.</span></span> <span data-ttu-id="6dd0c-179">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-179">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroup (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroup(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IContainerServicesOperations, resourceGroupName As String) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-180">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-181">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-181">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-182">指定されたリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-182">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-183">指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-183">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="6dd0c-184">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-184">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6dd0c-186">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-186">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6dd0c-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-188">指定されたリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-188">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-189">指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-189">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="6dd0c-190">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-190">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IContainerServicesOperations, nextPageLink As String) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-191">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6dd0c-192">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-192">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-193">指定されたリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-193">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-194">指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-194">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="6dd0c-195">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-195">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-196">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-196">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6dd0c-197">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-197">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6dd0c-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-199">指定されたリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-199">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-200">指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-200">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="6dd0c-201">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-201">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListNext (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt; ListNext(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IContainerServicesOperations, nextPageLink As String) As IPage(Of ContainerService)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-202">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-202">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6dd0c-203">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-203">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-204">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-204">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-205">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-205">Gets a list of container services in the specified subscription.</span></span> <span data-ttu-id="6dd0c-206">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-206">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IContainerServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.ContainerServicesOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.ContainerService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6dd0c-207">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-207">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6dd0c-208">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-208">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6dd0c-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6dd0c-210">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-210">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6dd0c-211">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-211">Gets a list of container services in the specified subscription.</span></span> <span data-ttu-id="6dd0c-212">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="6dd0c-212">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>