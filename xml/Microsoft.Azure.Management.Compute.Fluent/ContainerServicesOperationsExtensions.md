<Type Name="ContainerServicesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ContainerServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ContainerServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ContainerServicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="01174-101">ContainerServicesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="01174-101">Extension methods for ContainerServicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, containerServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01174-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01174-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01174-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-103">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="01174-104">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-104">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01174-105">作成または更新コンテナー サービス操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="01174-105">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01174-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01174-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01174-107">作成するか、コンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="01174-107">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="01174-108">作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="01174-108">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01174-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01174-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01174-110">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-110">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="01174-111">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-111">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01174-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01174-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01174-113">指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="01174-113">Deletes the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="01174-114">指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="01174-114">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="01174-115">操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。</span><span class="sxs-lookup"><span data-stu-id="01174-115">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="01174-116">コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。</span><span class="sxs-lookup"><span data-stu-id="01174-116">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, containerServiceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01174-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01174-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01174-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-118">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="01174-119">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-119">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="01174-120">作成または更新コンテナー サービス操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="01174-120">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01174-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01174-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01174-122">作成するか、コンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="01174-122">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="01174-123">作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="01174-123">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01174-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01174-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01174-125">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-125">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="01174-126">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-126">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01174-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01174-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01174-128">指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="01174-128">Deletes the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="01174-129">指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="01174-129">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="01174-130">操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。</span><span class="sxs-lookup"><span data-stu-id="01174-130">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="01174-131">コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。</span><span class="sxs-lookup"><span data-stu-id="01174-131">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, string containerServiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.GetAsync (operations, resourceGroupName, containerServiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01174-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01174-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01174-133">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-133">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="01174-134">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-134">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01174-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01174-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01174-136">指定されたコンテナー サービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="01174-136">Gets the properties of the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="01174-137">指定したサブスクリプションとリソース グループで指定されたコンテナー サービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="01174-137">Gets the properties of the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="01174-138">操作は、状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="01174-138">The operation returns the properties including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01174-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01174-139">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01174-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01174-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01174-141">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="01174-141">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="01174-142">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="01174-142">Gets a list of container services in the specified subscription.</span></span> <span data-ttu-id="01174-143">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="01174-143">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01174-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01174-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="01174-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="01174-145">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01174-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01174-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01174-147">指定されたリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="01174-147">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="01174-148">指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="01174-148">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="01174-149">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="01174-149">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01174-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01174-150">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="01174-151">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="01174-151">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01174-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01174-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01174-153">指定されたリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="01174-153">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="01174-154">指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="01174-154">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="01174-155">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="01174-155">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.ContainerServicesOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="01174-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="01174-156">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="01174-157">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="01174-157">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="01174-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="01174-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="01174-159">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="01174-159">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="01174-160">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="01174-160">Gets a list of container services in the specified subscription.</span></span> <span data-ttu-id="01174-161">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="01174-161">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>