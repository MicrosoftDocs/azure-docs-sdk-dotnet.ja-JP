<Type Name="AppServicePlansOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServicePlansOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServicePlansOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServicePlansOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServicePlansOperationsExtensions = class" />
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
            <span data-ttu-id="94a5b-101">AppServicePlansOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="94a5b-101">Extension methods for AppServicePlansOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, name, appServicePlan, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-104">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-104">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="94a5b-105">App Service の詳細を計画します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-105">Details of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-107">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-107">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-108">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-108">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner appServicePlan, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, appServicePlan, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-110">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-111">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-111">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="94a5b-112">App Service の詳細を計画します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-112">Details of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-114">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-114">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-115">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-115">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; CreateOrUpdateVnetRouteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; CreateOrUpdateVnetRouteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRouteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateVnetRouteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, route, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;CreateOrUpdateVnetRouteAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-117">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-117">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-118">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-118">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="94a5b-119">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-119">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="94a5b-120">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-120">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="94a5b-121">仮想ネットワーク ルートを定義します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-121">Definition of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-123">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-123">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-124">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-124">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-126">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-126">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-127">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-127">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-129">App Service プランを削除します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-129">Delete an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-130">App Service プランを削除します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-130">Delete an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteHybridConnectionAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteHybridConnectionAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteHybridConnectionAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteHybridConnectionAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;DeleteHybridConnectionAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-132">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-132">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-133">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-133">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="94a5b-134">Service Bus 名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-134">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="94a5b-135">Service Bus リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-135">Name of the Service Bus relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-137">App Service プラン内で使用するハイブリッド接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-137">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-138">App Service プラン内で使用するハイブリッド接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-138">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteVnetRouteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteVnetRouteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteVnetRouteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteVnetRouteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.DeleteVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;DeleteVnetRouteAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-140">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-140">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-141">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-141">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="94a5b-142">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-142">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="94a5b-143">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-143">Name of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-145">App Service プラン内の仮想ネットワーク ルートを削除します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-145">Delete a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-146">App Service プラン内の仮想ネットワーク ルートを削除します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-146">Delete a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-147">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-148">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-148">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-149">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-149">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-151">App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-151">Get an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-152">App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-152">Get an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt; GetHybridConnectionAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt; GetHybridConnectionAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetHybridConnectionAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetHybridConnectionAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetHybridConnectionAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-154">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-154">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-155">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-155">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="94a5b-156">Service Bus 名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-156">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="94a5b-157">Service Bus リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-157">Name of the Service Bus relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-159">App Service プラン内で使用するハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-159">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-160">App Service プラン内で使用するハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-160">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionPlanLimitAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt; GetHybridConnectionPlanLimitAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt; GetHybridConnectionPlanLimitAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimitAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetHybridConnectionPlanLimitAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimitAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetHybridConnectionPlanLimitAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionLimitsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-162">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-162">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-163">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-163">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-165">App Service プランで許可されているハイブリッド接続の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-165">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-166">App Service プランで許可されているハイブリッド接続の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-166">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRouteForVnetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; GetRouteForVnetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; GetRouteForVnetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetRouteForVnetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRouteForVnetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetRouteForVnetAsync (operations, resourceGroupName, name, vnetName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetRouteForVnetAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-168">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-168">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-169">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-169">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="94a5b-170">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-170">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="94a5b-171">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-171">Name of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-173">App Service プラン内の仮想ネットワーク ルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-173">Get a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-174">App Service プラン内の仮想ネットワーク ルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-174">Get a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetFromServerFarmAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt; GetVnetFromServerFarmAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt; GetVnetFromServerFarmAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetVnetFromServerFarmAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVnetFromServerFarmAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetVnetFromServerFarmAsync (operations, resourceGroupName, name, vnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetVnetFromServerFarmAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-176">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-176">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-177">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-177">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="94a5b-178">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-178">Name of the Virtual Network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-180">App Service プランに関連付けられている仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-180">Get a Virtual Network associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-181">App Service プランに関連付けられている仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-181">Get a Virtual Network associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetGatewayAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt; GetVnetGatewayAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt; GetVnetGatewayAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetVnetGatewayAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVnetGatewayAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.GetVnetGatewayAsync (operations, resourceGroupName, name, vnetName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;GetVnetGatewayAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-183">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-183">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-184">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-184">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="94a5b-185">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-185">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="94a5b-186">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-186">Name of the gateway.</span></span> <span data-ttu-id="94a5b-187">'Primary' のゲートウェイのみがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="94a5b-187">Only the 'primary' gateway is supported.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-189">仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-189">Get a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-190">仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-190">Get a Virtual Network gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, Nullable&lt;bool&gt; detailed = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, valuetype System.Nullable`1&lt;bool&gt; detailed, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListAsync (operations, detailed, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="detailed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-191">The operations group for this extension method.</span></span>
            </param>
        <param name="detailed">
            <span data-ttu-id="94a5b-192">指定&lt;コード&gt;true&lt;/code&gt;をすべての App Service プランのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-192">Specify &lt;code&gt;true&lt;/code&gt; to return all App Service plan properties.</span></span> <span data-ttu-id="94a5b-193">既定値は&lt;コード&gt;false&lt;/code&gt;プロパティのサブセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="94a5b-193">The default is &lt;code&gt;false&lt;/code&gt;, which returns a subset of the properties.</span></span>
            <span data-ttu-id="94a5b-194">すべてのプロパティの取得には、API の待機時間が増加します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-194">Retrieval of all properties may increase the API latency.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-195">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-196">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-196">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-197">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-197">Get all App Service plans for a subcription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-199">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-199">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-201">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-201">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-202">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-202">Get all App Service plans in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-203">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-203">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="94a5b-204">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-204">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-206">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-206">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-207">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-207">Get all App Service plans in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapabilitiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt; ListCapabilitiesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt; ListCapabilitiesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListCapabilitiesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapabilitiesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListCapabilitiesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListCapabilitiesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CapabilityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-209">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-209">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-210">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-210">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-211">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-212">App Service プランのすべての機能を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-212">List all capabilities of an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-213">App Service プランのすべての機能を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-213">List all capabilities of an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt; ListHybridConnectionKeysAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt; ListHybridConnectionKeysAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionKeysAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionKeysAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionKeysAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionKeysAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-215">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-215">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-216">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-216">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="94a5b-217">Service Bus 名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="94a5b-217">The name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="94a5b-218">Service Bus リレーの名前。</span><span class="sxs-lookup"><span data-stu-id="94a5b-218">The name of the Service Bus relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-220">ハイブリッド接続の値と送信のキーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-220">Get the send key name and value of a Hybrid Connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-221">ハイブリッド接続の値と送信のキーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-221">Get the send key name and value of a Hybrid Connection.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt; ListHybridConnectionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt; ListHybridConnectionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-222">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-222">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-223">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-223">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-224">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-224">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-226">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-226">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-227">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-227">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt; ListHybridConnectionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt; ListHybridConnectionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListHybridConnectionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionsNextAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-228">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-228">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="94a5b-229">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-229">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-230">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-230">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-231">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-231">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-232">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-232">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricDefintionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricDefintionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListMetricDefintionsAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
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
    <Member MemberName="ListMetricDefintionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricDefintionsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintionsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricDefintionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListMetricDefintionsNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
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
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, name, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListMetricsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-234">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-234">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-235">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-235">Name of the App Service plan.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="94a5b-236">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="94a5b-236">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="94a5b-237">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-237">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="94a5b-238">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-238">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="94a5b-239">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-239">Filter conforms to odata syntax.</span></span> <span data-ttu-id="94a5b-240">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="94a5b-240">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-241">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-241">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-242">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-242">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-243">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-243">Get metrics for an App Serice plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListMetricsNextAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-244">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-244">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="94a5b-245">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-245">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-246">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-247">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-247">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-248">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-248">Get metrics for an App Serice plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-249">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-249">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="94a5b-250">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-250">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-251">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-251">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-252">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-252">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-253">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-253">Get all App Service plans for a subcription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesForVnetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; ListRoutesForVnetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt; ListRoutesForVnetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListRoutesForVnetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesForVnetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListRoutesForVnetAsync (operations, resourceGroupName, name, vnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListRoutesForVnetAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-254">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-254">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-255">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-255">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-256">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-256">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="94a5b-257">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-257">Name of the Virtual Network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-258">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-259">App Service プラン内の仮想ネットワークに関連付けられているすべてのルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-259">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-260">App Service プラン内の仮想ネットワークに関連付けられているすべてのルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-260">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVnetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt; ListVnetsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt; ListVnetsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListVnetsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVnetsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListVnetsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListVnetsAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-261">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-261">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-262">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-262">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-263">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-263">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-264">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-264">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-265">App Service プランに関連付けられているすべての仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-265">Get all Virtual Networks associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-266">App Service プランに関連付けられているすべての仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-266">Get all Virtual Networks associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken = null, string filter = null, string top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken, string filter, string top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsAsync (operations, resourceGroupName, name, skipToken, filter, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListWebAppsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-267">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-267">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-268">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-268">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-269">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-269">Name of the App Service plan.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="94a5b-270">App service プランに関連付けられている webapps の一覧で web アプリに進んでください。</span><span class="sxs-lookup"><span data-stu-id="94a5b-270">Skip to a web app in the list of webapps associated with app service plan.</span></span>
            <span data-ttu-id="94a5b-271">指定した場合、結果のリスト (など)、skipToken から web アプリが含まれます。</span><span class="sxs-lookup"><span data-stu-id="94a5b-271">If specified, the resulting list will contain web apps starting from (including) the skipToken.</span></span> <span data-ttu-id="94a5b-272">それ以外の場合、結果のリストが一覧の先頭からの web アプリが含まれます</span><span class="sxs-lookup"><span data-stu-id="94a5b-272">Otherwise, the resulting list contains web apps from the start of the list</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="94a5b-273">サポートされているフィルター: $filter を実行している状態 eq を = です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-273">Supported filter: $filter=state eq running.</span></span> <span data-ttu-id="94a5b-274">現在実行されている web アプリのみを返します</span><span class="sxs-lookup"><span data-stu-id="94a5b-274">Returns only web apps that are currently running</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="94a5b-275">ページ サイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-275">List page size.</span></span> <span data-ttu-id="94a5b-276">指定すると、結果がページングされています。</span><span class="sxs-lookup"><span data-stu-id="94a5b-276">If specified, results are paged.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-277">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-277">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-278">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-278">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-279">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-279">Get all apps associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListWebAppsByHybridConnectionAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListWebAppsByHybridConnectionAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnectionAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListWebAppsByHybridConnectionAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-280">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-280">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-281">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-281">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-282">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-282">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="94a5b-283">ハイブリッド接続の名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-283">Name of the Hybrid Connection namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="94a5b-284">ハイブリッド接続リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-284">Name of the Hybrid Connection relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-285">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-285">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-286">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-286">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-287">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-287">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListWebAppsByHybridConnectionNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListWebAppsByHybridConnectionNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnectionNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListWebAppsByHybridConnectionNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-288">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-288">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="94a5b-289">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-289">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-290">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-290">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-291">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-291">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-292">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-292">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt; ListWebAppsNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.ListWebAppsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;ListWebAppsNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-293">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-293">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="94a5b-294">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-294">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-295">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-295">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-296">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-296">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-297">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-297">Get all apps associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootWorkerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RebootWorkerAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RebootWorkerAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.RebootWorkerAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebootWorkerAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.RebootWorkerAsync (operations, resourceGroupName, name, workerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;RebootWorkerAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-298">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-298">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-299">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-299">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-300">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-300">Name of the App Service plan.</span></span>
            </param>
        <param name="workerName">
            <span data-ttu-id="94a5b-301">通常 RD. で始まるワーカー コンピューターの名前</span><span class="sxs-lookup"><span data-stu-id="94a5b-301">Name of worker machine, which typically starts with RD.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-302">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-302">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-303">App Service プラン内のワーカーのコンピューターを再起動します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-303">Reboot a worker machine in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-304">App Service プラン内のワーカーのコンピューターを再起動します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-304">Reboot a worker machine in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RestartWebAppsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; softRestart = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RestartWebAppsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; softRestart, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.RestartWebAppsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartWebAppsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.RestartWebAppsAsync (operations, resourceGroupName, name, softRestart, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;RestartWebAppsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="softRestart" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-305">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-305">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-306">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-306">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-307">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-307">Name of the App Service plan.</span></span>
            </param>
        <param name="softRestart">
            <span data-ttu-id="94a5b-308">指定&lt;コード&gt;true&lt;/code&gt;かからず、ソフト再起動、構成設定を適用し、必要に応じて、アプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-308">Specify &lt;code&gt;true&lt;/code&gt; to performa a soft restart, applies the configuration settings and restarts the apps if necessary.</span></span> <span data-ttu-id="94a5b-309">既定値は&lt;コード&gt;false&lt;/code&gt;を常に再起動し、アプリを reprovisions</span><span class="sxs-lookup"><span data-stu-id="94a5b-309">The default is &lt;code&gt;false&lt;/code&gt;, which always restarts and reprovisions the apps</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-310">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-310">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-311">App Service プラン内のすべてのアプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-311">Restart all apps in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-312">App Service プラン内のすべてのアプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-312">Restart all apps in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetGatewayAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt; UpdateVnetGatewayAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner connectionEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt; UpdateVnetGatewayAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, class Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner connectionEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.UpdateVnetGatewayAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateVnetGatewayAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.UpdateVnetGatewayAsync (operations, resourceGroupName, name, vnetName, gatewayName, connectionEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;UpdateVnetGatewayAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="connectionEnvelope" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VnetGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-313">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-313">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-314">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-314">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-315">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-315">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="94a5b-316">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-316">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="94a5b-317">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-317">Name of the gateway.</span></span> <span data-ttu-id="94a5b-318">'Primary' のゲートウェイのみがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="94a5b-318">Only the 'primary' gateway is supported.</span></span>
            </param>
        <param name="connectionEnvelope">
            <span data-ttu-id="94a5b-319">ゲートウェイの定義です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-319">Definition of the gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-320">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-320">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-321">仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-321">Update a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-322">仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-322">Update a Virtual Network gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; UpdateVnetRouteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; UpdateVnetRouteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner route, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.UpdateVnetRouteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateVnetRouteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions.UpdateVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, route, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServicePlansOperationsExtensions/&lt;UpdateVnetRouteAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="94a5b-323">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="94a5b-323">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="94a5b-324">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-324">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="94a5b-325">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-325">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="94a5b-326">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-326">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="94a5b-327">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="94a5b-327">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="94a5b-328">仮想ネットワーク ルートを定義します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-328">Definition of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="94a5b-329">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="94a5b-329">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="94a5b-330">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-330">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="94a5b-331">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="94a5b-331">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>