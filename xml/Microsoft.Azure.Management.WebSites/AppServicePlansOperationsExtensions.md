<Type Name="AppServicePlansOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServicePlansOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServicePlansOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServicePlansOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServicePlansOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e8d0d-101">AppServicePlansOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-101">Extension methods for AppServicePlansOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServicePlan BeginCreateOrUpdate (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServicePlan BeginCreateOrUpdate(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlan -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlan" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, name, appServicePlan)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServicePlan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlan" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-104">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-104">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="e8d0d-105">App Service の詳細を計画します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-105">Details of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-106">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-106">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-107">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-107">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, name, appServicePlan, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-109">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-109">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-110">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-110">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="e8d0d-111">App Service の詳細を計画します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-111">Details of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-113">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-113">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-114">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-114">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServicePlan CreateOrUpdate (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServicePlan CreateOrUpdate(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlan -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlan" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, name, appServicePlan)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServicePlan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlan" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-116">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-116">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-117">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-117">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="e8d0d-118">App Service の詳細を計画します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-118">Details of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-119">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-119">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-120">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-120">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlan appServicePlan, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, name, appServicePlan, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-122">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-122">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-123">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-123">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="e8d0d-124">App Service の詳細を計画します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-124">Details of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-126">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-126">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-127">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-127">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateVnetRoute">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetRoute CreateOrUpdateVnetRoute (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.WebSites.Models.VnetRoute route);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetRoute CreateOrUpdateVnetRoute(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.WebSites.Models.VnetRoute route) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRoute(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetRoute)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateVnetRoute (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, routeName As String, route As VnetRoute) As VnetRoute" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateVnetRoute : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetRoute -&gt; Microsoft.Azure.Management.WebSites.Models.VnetRoute" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRoute (operations, resourceGroupName, name, vnetName, routeName, route)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetRoute</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.WebSites.Models.VnetRoute" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-129">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-129">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-130">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-130">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-131">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-131">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="e8d0d-132">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-132">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="e8d0d-133">仮想ネットワーク ルートを定義します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-133">Definition of the Virtual Network route.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-134">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-134">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-135">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-135">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; CreateOrUpdateVnetRouteAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.WebSites.Models.VnetRoute route, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; CreateOrUpdateVnetRouteAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.WebSites.Models.VnetRoute route, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRouteAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetRoute,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateVnetRouteAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetRoute * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.CreateOrUpdateVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, route, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;CreateOrUpdateVnetRouteAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.WebSites.Models.VnetRoute" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-137">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-137">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-138">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-138">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-139">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-139">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="e8d0d-140">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-140">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="e8d0d-141">仮想ネットワーク ルートを定義します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-141">Definition of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-143">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-143">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-144">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-144">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Delete(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IAppServicePlansOperations, resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Delete (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-146">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-146">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-147">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-147">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-148">App Service プランを削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-148">Delete an App Service plan.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="e8d0d-149">App Service プランを削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-149">Delete an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-151">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-152">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-152">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-154">App Service プランを削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-154">Delete an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-155">App Service プランを削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-155">Delete an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteHybridConnection">
      <MemberSignature Language="C#" Value="public static void DeleteHybridConnection (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteHybridConnection(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteHybridConnection(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteHybridConnection (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, namespaceName As String, relayName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteHybridConnection : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteHybridConnection (operations, resourceGroupName, name, namespaceName, relayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-157">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-157">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-158">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-158">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e8d0d-159">Service Bus 名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-159">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="e8d0d-160">Service Bus リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-160">Name of the Service Bus relay.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-161">App Service プラン内で使用するハイブリッド接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-161">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="e8d0d-162">App Service プラン内で使用するハイブリッド接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-162">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteHybridConnectionAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteHybridConnectionAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteHybridConnectionAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteHybridConnectionAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;DeleteHybridConnectionAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-164">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-164">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-165">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-165">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e8d0d-166">Service Bus 名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-166">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="e8d0d-167">Service Bus リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-167">Name of the Service Bus relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-169">App Service プラン内で使用するハイブリッド接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-169">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-170">App Service プラン内で使用するハイブリッド接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-170">Delete a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteVnetRoute">
      <MemberSignature Language="C#" Value="public static void DeleteVnetRoute (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteVnetRoute(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteVnetRoute(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteVnetRoute (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, routeName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteVnetRoute : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteVnetRoute (operations, resourceGroupName, name, vnetName, routeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-172">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-172">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-173">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-173">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-174">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-174">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="e8d0d-175">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-175">Name of the Virtual Network route.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-176">App Service プラン内の仮想ネットワーク ルートを削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-176">Delete a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="e8d0d-177">App Service プラン内の仮想ネットワーク ルートを削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-177">Delete a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteVnetRouteAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteVnetRouteAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteVnetRouteAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteVnetRouteAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.DeleteVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;DeleteVnetRouteAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-178">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-179">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-179">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-180">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-180">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-181">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-181">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="e8d0d-182">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-182">Name of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-184">App Service プラン内の仮想ネットワーク ルートを削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-184">Delete a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-185">App Service プラン内の仮想ネットワーク ルートを削除します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-185">Delete a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServicePlan Get (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServicePlan Get(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Get(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As AppServicePlan" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlan" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Get (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServicePlan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-187">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-187">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-188">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-188">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-189">App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-189">Get an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-190">App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-190">Get an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; GetAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; GetAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-191">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-192">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-192">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-193">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-193">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-195">App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-195">Get an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-196">App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-196">Get an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.HybridConnection GetHybridConnection (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.HybridConnection GetHybridConnection(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnection(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetHybridConnection (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, namespaceName As String, relayName As String) As HybridConnection" />
      <MemberSignature Language="F#" Value="static member GetHybridConnection : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HybridConnection" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnection (operations, resourceGroupName, name, namespaceName, relayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HybridConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-198">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-198">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-199">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-199">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e8d0d-200">Service Bus 名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-200">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="e8d0d-201">Service Bus リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-201">Name of the Service Bus relay.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-202">App Service プラン内で使用するハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-202">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-203">App Service プラン内で使用するハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-203">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; GetHybridConnectionAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; GetHybridConnectionAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetHybridConnectionAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetHybridConnectionAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-205">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-205">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-206">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-206">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e8d0d-207">Service Bus 名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-207">Name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="e8d0d-208">Service Bus リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-208">Name of the Service Bus relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-210">App Service プラン内で使用するハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-210">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-211">App Service プラン内で使用するハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-211">Retrieve a Hybrid Connection in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionPlanLimit">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits GetHybridConnectionPlanLimit (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits GetHybridConnectionPlanLimit(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimit(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetHybridConnectionPlanLimit (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As HybridConnectionLimits" />
      <MemberSignature Language="F#" Value="static member GetHybridConnectionPlanLimit : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimit (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-212">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-212">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-213">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-213">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-214">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-214">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-215">App Service プランで許可されているハイブリッド接続の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-215">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-216">App Service プランで許可されているハイブリッド接続の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-216">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHybridConnectionPlanLimitAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits&gt; GetHybridConnectionPlanLimitAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits&gt; GetHybridConnectionPlanLimitAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimitAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetHybridConnectionPlanLimitAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetHybridConnectionPlanLimitAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetHybridConnectionPlanLimitAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionLimits&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-217">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-217">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-218">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-218">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-219">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-219">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-220">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-221">App Service プランで許可されているハイブリッド接続の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-221">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-222">App Service プランで許可されているハイブリッド接続の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-222">Get the maximum number of Hybrid Connections allowed in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRouteForVnet">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; GetRouteForVnet (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; GetRouteForVnet(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetRouteForVnet(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRouteForVnet (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, routeName As String) As IList(Of VnetRoute)" />
      <MemberSignature Language="F#" Value="static member GetRouteForVnet : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetRouteForVnet (operations, resourceGroupName, name, vnetName, routeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-224">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-224">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-225">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-225">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-226">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-226">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="e8d0d-227">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-227">Name of the Virtual Network route.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-228">App Service プラン内の仮想ネットワーク ルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-228">Get a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-229">App Service プラン内の仮想ネットワーク ルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-229">Get a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRouteForVnetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt; GetRouteForVnetAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt; GetRouteForVnetAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetRouteForVnetAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRouteForVnetAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetRouteForVnetAsync (operations, resourceGroupName, name, vnetName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetRouteForVnetAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-230">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-230">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-231">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-231">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-232">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-232">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-233">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-233">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="e8d0d-234">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-234">Name of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-235">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-236">App Service プラン内の仮想ネットワーク ルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-236">Get a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-237">App Service プラン内の仮想ネットワーク ルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-237">Get a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServerFarmSkus">
      <MemberSignature Language="C#" Value="public static object GetServerFarmSkus (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object GetServerFarmSkus(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetServerFarmSkus(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetServerFarmSkus (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As Object" />
      <MemberSignature Language="F#" Value="static member GetServerFarmSkus : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; obj" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetServerFarmSkus (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-238">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-238">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-239">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-239">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-240">App Service プランの名前</span><span class="sxs-lookup"><span data-stu-id="e8d0d-240">Name of App Service Plan</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-241">指定された App Service プランの選択可能なすべての sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-241">Gets all selectable sku's for a given App Service Plan</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-242">指定された App Service プランの選択可能なすべての sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-242">Gets all selectable sku's for a given App Service Plan</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServerFarmSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;object&gt; GetServerFarmSkusAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;object&gt; GetServerFarmSkusAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetServerFarmSkusAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetServerFarmSkusAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetServerFarmSkusAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetServerFarmSkusAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-244">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-244">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-245">App Service プランの名前</span><span class="sxs-lookup"><span data-stu-id="e8d0d-245">Name of App Service Plan</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-246">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-247">指定された App Service プランの選択可能なすべての sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-247">Gets all selectable sku's for a given App Service Plan</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-248">指定された App Service プランの選択可能なすべての sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-248">Gets all selectable sku's for a given App Service Plan</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetFromServerFarm">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetInfo GetVnetFromServerFarm (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetInfo GetVnetFromServerFarm(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetFromServerFarm(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVnetFromServerFarm (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String) As VnetInfo" />
      <MemberSignature Language="F#" Value="static member GetVnetFromServerFarm : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.VnetInfo" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetFromServerFarm (operations, resourceGroupName, name, vnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-249">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-249">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-250">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-250">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-251">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-251">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-252">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-252">Name of the Virtual Network.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-253">App Service プランに関連付けられている仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-253">Get a Virtual Network associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-254">App Service プランに関連付けられている仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-254">Get a Virtual Network associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetFromServerFarmAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt; GetVnetFromServerFarmAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt; GetVnetFromServerFarmAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetFromServerFarmAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVnetFromServerFarmAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetFromServerFarmAsync (operations, resourceGroupName, name, vnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetVnetFromServerFarmAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-255">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-256">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-256">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-257">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-257">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-258">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-258">Name of the Virtual Network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-259">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-259">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-260">App Service プランに関連付けられている仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-260">Get a Virtual Network associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-261">App Service プランに関連付けられている仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-261">Get a Virtual Network associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetGateway">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetGateway GetVnetGateway (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetGateway GetVnetGateway(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetGateway(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVnetGateway (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, gatewayName As String) As VnetGateway" />
      <MemberSignature Language="F#" Value="static member GetVnetGateway : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.VnetGateway" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetGateway (operations, resourceGroupName, name, vnetName, gatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-262">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-262">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-263">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-263">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-264">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-264">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-265">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-265">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="e8d0d-266">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-266">Name of the gateway.</span></span> <span data-ttu-id="e8d0d-267">'Primary' のゲートウェイのみがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-267">Only the 'primary' gateway is supported.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-268">仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-268">Get a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-269">仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-269">Get a Virtual Network gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVnetGatewayAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt; GetVnetGatewayAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt; GetVnetGatewayAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetGatewayAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVnetGatewayAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.GetVnetGatewayAsync (operations, resourceGroupName, name, vnetName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;GetVnetGatewayAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-270">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-270">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-271">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-271">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-272">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-272">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-273">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-273">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="e8d0d-274">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-274">Name of the gateway.</span></span> <span data-ttu-id="e8d0d-275">'Primary' のゲートウェイのみがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-275">Only the 'primary' gateway is supported.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-276">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-276">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-277">仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-277">Get a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-278">仮想ネットワーク ゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-278">Get a Virtual Network gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; List (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, Nullable&lt;bool&gt; detailed = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; List(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, valuetype System.Nullable`1&lt;bool&gt; detailed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.List(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAppServicePlansOperations, Optional detailed As Nullable(Of Boolean) = null) As IPage(Of AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.List (operations, detailed)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="detailed" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-279">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-279">The operations group for this extension method.</span></span>
            </param>
        <param name="detailed">
            <span data-ttu-id="e8d0d-280">指定&lt;コード&gt;true&lt;/code&gt;をすべての App Service プランのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-280">Specify &lt;code&gt;true&lt;/code&gt; to return all App Service plan properties.</span></span> <span data-ttu-id="e8d0d-281">既定値は&lt;コード&gt;false&lt;/code&gt;プロパティのサブセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-281">The default is &lt;code&gt;false&lt;/code&gt;, which returns a subset of the properties.</span></span>
            <span data-ttu-id="e8d0d-282">すべてのプロパティの取得には、API の待機時間が増加します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-282">Retrieval of all properties may increase the API latency.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-283">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-283">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-284">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-284">Get all App Service plans for a subcription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, Nullable&lt;bool&gt; detailed = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, valuetype System.Nullable`1&lt;bool&gt; detailed, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListAsync (operations, detailed, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="detailed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-285">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-285">The operations group for this extension method.</span></span>
            </param>
        <param name="detailed">
            <span data-ttu-id="e8d0d-286">指定&lt;コード&gt;true&lt;/code&gt;をすべての App Service プランのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-286">Specify &lt;code&gt;true&lt;/code&gt; to return all App Service plan properties.</span></span> <span data-ttu-id="e8d0d-287">既定値は&lt;コード&gt;false&lt;/code&gt;プロパティのサブセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-287">The default is &lt;code&gt;false&lt;/code&gt;, which returns a subset of the properties.</span></span>
            <span data-ttu-id="e8d0d-288">すべてのプロパティの取得には、API の待機時間が増加します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-288">Retrieval of all properties may increase the API latency.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-289">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-289">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-290">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-290">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-291">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-291">Get all App Service plans for a subcription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListByResourceGroup (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListByResourceGroup(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IAppServicePlansOperations, resourceGroupName As String) As IPage(Of AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-292">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-292">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-293">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-293">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-294">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-294">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-295">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-295">Get all App Service plans in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-296">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-296">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-297">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-297">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-298">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-298">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-299">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-299">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-300">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-300">Get all App Service plans in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-301">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-301">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-302">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-302">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-303">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-303">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-304">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-304">Get all App Service plans in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-305">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-305">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-306">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-306">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-307">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-307">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-308">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-308">Get all App Service plans in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-309">リソース グループ内のすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-309">Get all App Service plans in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapabilities">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt; ListCapabilities (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Capability&gt; ListCapabilities(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListCapabilities(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCapabilities (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As IList(Of Capability)" />
      <MemberSignature Language="F#" Value="static member ListCapabilities : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListCapabilities (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-310">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-310">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-311">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-311">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-312">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-312">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-313">App Service プランのすべての機能を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-313">List all capabilities of an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-314">App Service プランのすべての機能を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-314">List all capabilities of an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCapabilitiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;&gt; ListCapabilitiesAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Capability&gt;&gt; ListCapabilitiesAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListCapabilitiesAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCapabilitiesAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListCapabilitiesAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListCapabilitiesAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-315">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-315">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-316">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-316">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-317">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-317">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-318">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-318">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-319">App Service プランのすべての機能を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-319">List all capabilities of an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-320">App Service プランのすべての機能を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-320">List all capabilities of an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey ListHybridConnectionKeys (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey ListHybridConnectionKeys(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionKeys(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHybridConnectionKeys (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, namespaceName As String, relayName As String) As HybridConnectionKey" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionKeys : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionKeys (operations, resourceGroupName, name, namespaceName, relayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-321">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-321">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-322">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-322">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-323">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-323">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e8d0d-324">Service Bus 名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-324">The name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="e8d0d-325">Service Bus リレーの名前。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-325">The name of the Service Bus relay.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-326">ハイブリッド接続の値と送信のキーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-326">Get the send key name and value of a Hybrid Connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-327">ハイブリッド接続の値と送信のキーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-327">Get the send key name and value of a Hybrid Connection.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey&gt; ListHybridConnectionKeysAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey&gt; ListHybridConnectionKeysAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionKeysAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionKeysAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionKeysAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionKeysAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnectionKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-328">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-328">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-329">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-329">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-330">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-330">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e8d0d-331">Service Bus 名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-331">The name of the Service Bus namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="e8d0d-332">Service Bus リレーの名前。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-332">The name of the Service Bus relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-333">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-333">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-334">ハイブリッド接続の値と送信のキーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-334">Get the send key name and value of a Hybrid Connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-335">ハイブリッド接続の値と送信のキーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-335">Get the send key name and value of a Hybrid Connection.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnections">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; ListHybridConnections (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; ListHybridConnections(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnections(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHybridConnections (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As IPage(Of HybridConnection)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnections : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnections (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-336">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-336">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-337">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-337">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-338">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-338">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-339">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-339">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-340">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-340">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt; ListHybridConnectionsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt; ListHybridConnectionsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionsAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-341">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-341">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-342">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-342">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-343">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-343">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-344">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-344">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-345">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-345">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-346">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-346">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; ListHybridConnectionsNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; ListHybridConnectionsNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHybridConnectionsNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of HybridConnection)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionsNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-347">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-347">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-348">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-348">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-349">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-349">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-350">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-350">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHybridConnectionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt; ListHybridConnectionsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt; ListHybridConnectionsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHybridConnectionsNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListHybridConnectionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListHybridConnectionsNextAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-351">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-351">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-352">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-352">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-353">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-353">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-354">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-354">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-355">App Service プランで使用中のすべてのハイブリッド接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-355">Retrieve all Hybrid Connections in use in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMetricDefintions (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMetricDefintions(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintions(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefintions (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintions : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintions (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-356">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-356">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-357">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-357">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-358">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-358">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-359">App Service プランとその定義のクエリ可能なメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-359">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-360">App Service プランとその定義のクエリ可能なメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-360">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintionsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListMetricDefintionsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-361">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-361">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-362">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-362">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-363">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-363">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-364">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-364">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-365">App Service プランとその定義のクエリ可能なメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-365">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-366">App Service プランとその定義のクエリ可能なメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-366">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMetricDefintionsNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt; ListMetricDefintionsNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefintionsNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of ResourceMetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintionsNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-367">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-367">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-368">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-368">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-369">App Service プランとその定義のクエリ可能なメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-369">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-370">App Service プランとその定義のクエリ可能なメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-370">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefintionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt; ListMetricDefintionsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefintionsNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricDefintionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListMetricDefintionsNextAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-371">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-371">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-372">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-372">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-373">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-373">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-374">App Service プランとその定義のクエリ可能なメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-374">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-375">App Service プランとその定義のクエリ可能なメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-375">Get metrics that can be queried for an App Service plan, and their definitions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetrics (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetrics(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetrics(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, Optional details As Nullable(Of Boolean) = null, Optional filter As String = null) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetrics (operations, resourceGroupName, name, details, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-376">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-376">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-377">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-377">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-378">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-378">Name of the App Service plan.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="e8d0d-379">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-379">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="e8d0d-380">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-380">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="e8d0d-381">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-381">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="e8d0d-382">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-382">Filter conforms to odata syntax.</span></span> <span data-ttu-id="e8d0d-383">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-383">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-384">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-384">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-385">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-385">Get metrics for an App Serice plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, name, details, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListMetricsAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-386">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-386">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-387">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-387">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-388">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-388">Name of the App Service plan.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="e8d0d-389">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-389">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span> <span data-ttu-id="e8d0d-390">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-390">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="e8d0d-391">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-391">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="e8d0d-392">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-392">Filter conforms to odata syntax.</span></span> <span data-ttu-id="e8d0d-393">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-393">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-394">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-394">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-395">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-395">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-396">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-396">Get metrics for an App Serice plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetricsNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt; ListMetricsNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricsNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of ResourceMetric)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-397">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-397">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-398">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-398">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-399">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-399">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-400">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-400">Get metrics for an App Serice plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt; ListMetricsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListMetricsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListMetricsNextAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-401">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-401">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-402">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-402">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-403">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-403">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-404">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-404">Get metrics for an App Serice plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-405">アプリ サービス プランのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-405">Get metrics for an App Serice plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; ListNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of AppServicePlan)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-406">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-406">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-407">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-407">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-408">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-408">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-409">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-409">Get all App Service plans for a subcription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListNextAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-410">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-410">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-411">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-411">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-412">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-412">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-413">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-413">Get all App Service plans for a subcription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-414">サブスクリプションのすべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-414">Get all App Service plans for a subcription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesForVnet">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; ListRoutesForVnet (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; ListRoutesForVnet(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListRoutesForVnet(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRoutesForVnet (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String) As IList(Of VnetRoute)" />
      <MemberSignature Language="F#" Value="static member ListRoutesForVnet : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListRoutesForVnet (operations, resourceGroupName, name, vnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-415">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-415">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-416">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-416">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-417">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-417">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-418">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-418">Name of the Virtual Network.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-419">App Service プラン内の仮想ネットワークに関連付けられているすべてのルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-419">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-420">App Service プラン内の仮想ネットワークに関連付けられているすべてのルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-420">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesForVnetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt; ListRoutesForVnetAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt; ListRoutesForVnetAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListRoutesForVnetAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesForVnetAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListRoutesForVnetAsync (operations, resourceGroupName, name, vnetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListRoutesForVnetAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-421">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-421">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-422">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-422">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-423">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-423">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-424">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-424">Name of the Virtual Network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-425">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-425">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-426">App Service プラン内の仮想ネットワークに関連付けられているすべてのルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-426">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-427">App Service プラン内の仮想ネットワークに関連付けられているすべてのルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-427">Get all routes that are associated with a Virtual Network in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsages">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsages (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsages(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsages(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListUsages (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, Optional filter As String = null) As IPage(Of CsmUsageQuota)" />
      <MemberSignature Language="F#" Value="static member ListUsages : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsages (operations, resourceGroupName, name, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-428">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-428">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-429">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-429">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-430">App Service プランの名前</span><span class="sxs-lookup"><span data-stu-id="e8d0d-430">Name of App Service Plan</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="e8d0d-431">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-431">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="e8d0d-432">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-432">Filter conforms to odata syntax.</span></span> <span data-ttu-id="e8d0d-433">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2')。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-433">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2').</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-434">サーバー ファームの使用状況情報を取得します</span><span class="sxs-lookup"><span data-stu-id="e8d0d-434">Gets server farm usage information</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-435">サーバー ファームの使用状況情報を取得します</span><span class="sxs-lookup"><span data-stu-id="e8d0d-435">Gets server farm usage information</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, name, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListUsagesAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-436">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-436">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-437">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-437">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-438">App Service プランの名前</span><span class="sxs-lookup"><span data-stu-id="e8d0d-438">Name of App Service Plan</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="e8d0d-439">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-439">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="e8d0d-440">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-440">Filter conforms to odata syntax.</span></span> <span data-ttu-id="e8d0d-441">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2')。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-441">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2').</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-442">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-442">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-443">サーバー ファームの使用状況情報を取得します</span><span class="sxs-lookup"><span data-stu-id="e8d0d-443">Gets server farm usage information</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-444">サーバー ファームの使用状況情報を取得します</span><span class="sxs-lookup"><span data-stu-id="e8d0d-444">Gets server farm usage information</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsagesNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt; ListUsagesNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListUsagesNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of CsmUsageQuota)" />
      <MemberSignature Language="F#" Value="static member ListUsagesNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-445">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-445">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-446">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-446">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-447">サーバー ファームの使用状況情報を取得します</span><span class="sxs-lookup"><span data-stu-id="e8d0d-447">Gets server farm usage information</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-448">サーバー ファームの使用状況情報を取得します</span><span class="sxs-lookup"><span data-stu-id="e8d0d-448">Gets server farm usage information</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt; ListUsagesNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListUsagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListUsagesNextAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-449">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-449">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-450">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-450">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-451">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-451">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-452">サーバー ファームの使用状況情報を取得します</span><span class="sxs-lookup"><span data-stu-id="e8d0d-452">Gets server farm usage information</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-453">サーバー ファームの使用状況情報を取得します</span><span class="sxs-lookup"><span data-stu-id="e8d0d-453">Gets server farm usage information</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVnets">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt; ListVnets (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt; ListVnets(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListVnets(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListVnets (operations As IAppServicePlansOperations, resourceGroupName As String, name As String) As IList(Of VnetInfo)" />
      <MemberSignature Language="F#" Value="static member ListVnets : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListVnets (operations, resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-454">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-454">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-455">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-455">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-456">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-456">Name of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-457">App Service プランに関連付けられているすべての仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-457">Get all Virtual Networks associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-458">App Service プランに関連付けられているすべての仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-458">Get all Virtual Networks associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVnetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;&gt; ListVnetsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;&gt; ListVnetsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListVnetsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVnetsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListVnetsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListVnetsAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-459">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-459">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-460">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-460">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-461">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-461">Name of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-462">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-462">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-463">App Service プランに関連付けられているすべての仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-463">Get all Virtual Networks associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-464">App Service プランに関連付けられているすべての仮想ネットワークを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-464">Get all Virtual Networks associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebApps">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebApps (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken = null, string filter = null, string top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebApps(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken, string filter, string top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebApps(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebApps (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, Optional skipToken As String = null, Optional filter As String = null, Optional top As String = null) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member ListWebApps : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebApps (operations, resourceGroupName, name, skipToken, filter, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-465">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-465">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-466">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-466">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-467">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-467">Name of the App Service plan.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="e8d0d-468">App service プランに関連付けられている webapps の一覧で web アプリに進んでください。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-468">Skip to a web app in the list of webapps associated with app service plan.</span></span>
            <span data-ttu-id="e8d0d-469">指定した場合、結果のリスト (など)、skipToken から web アプリが含まれます。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-469">If specified, the resulting list will contain web apps starting from (including) the skipToken.</span></span> <span data-ttu-id="e8d0d-470">それ以外の場合、結果のリストが一覧の先頭からの web アプリが含まれます</span><span class="sxs-lookup"><span data-stu-id="e8d0d-470">Otherwise, the resulting list contains web apps from the start of the list</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="e8d0d-471">サポートされているフィルター: $filter を実行している状態 eq を = です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-471">Supported filter: $filter=state eq running.</span></span> <span data-ttu-id="e8d0d-472">現在実行されている web アプリのみを返します</span><span class="sxs-lookup"><span data-stu-id="e8d0d-472">Returns only web apps that are currently running</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="e8d0d-473">ページ サイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-473">List page size.</span></span> <span data-ttu-id="e8d0d-474">指定すると、結果がページングされています。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-474">If specified, results are paged.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-475">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-475">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-476">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-476">Get all apps associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken = null, string filter = null, string top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string skipToken, string filter, string top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsAsync (operations, resourceGroupName, name, skipToken, filter, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListWebAppsAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="skipToken" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-477">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-477">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-478">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-478">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-479">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-479">Name of the App Service plan.</span></span>
            </param>
        <param name="skipToken">
            <span data-ttu-id="e8d0d-480">App service プランに関連付けられている webapps の一覧で web アプリに進んでください。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-480">Skip to a web app in the list of webapps associated with app service plan.</span></span>
            <span data-ttu-id="e8d0d-481">指定した場合、結果のリスト (など)、skipToken から web アプリが含まれます。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-481">If specified, the resulting list will contain web apps starting from (including) the skipToken.</span></span> <span data-ttu-id="e8d0d-482">それ以外の場合、結果のリストが一覧の先頭からの web アプリが含まれます</span><span class="sxs-lookup"><span data-stu-id="e8d0d-482">Otherwise, the resulting list contains web apps from the start of the list</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="e8d0d-483">サポートされているフィルター: $filter を実行している状態 eq を = です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-483">Supported filter: $filter=state eq running.</span></span> <span data-ttu-id="e8d0d-484">現在実行されている web アプリのみを返します</span><span class="sxs-lookup"><span data-stu-id="e8d0d-484">Returns only web apps that are currently running</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="e8d0d-485">ページ サイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-485">List page size.</span></span> <span data-ttu-id="e8d0d-486">指定すると、結果がページングされています。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-486">If specified, results are paged.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-487">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-487">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-488">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-488">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-489">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-489">Get all apps associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnection">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;string&gt; ListWebAppsByHybridConnection (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;string&gt; ListWebAppsByHybridConnection(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnection(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebAppsByHybridConnection (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, namespaceName As String, relayName As String) As IPage(Of String)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnection : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnection (operations, resourceGroupName, name, namespaceName, relayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-490">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-490">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-491">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-491">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-492">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-492">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e8d0d-493">ハイブリッド接続の名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-493">Name of the Hybrid Connection namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="e8d0d-494">ハイブリッド接続リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-494">Name of the Hybrid Connection relay.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-495">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-495">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-496">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-496">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListWebAppsByHybridConnectionAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListWebAppsByHybridConnectionAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string namespaceName, string relayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnectionAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionAsync (operations, resourceGroupName, name, namespaceName, relayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListWebAppsByHybridConnectionAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="relayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-497">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-497">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-498">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-498">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-499">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-499">Name of the App Service plan.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e8d0d-500">ハイブリッド接続の名前空間の名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-500">Name of the Hybrid Connection namespace.</span></span>
            </param>
        <param name="relayName">
            <span data-ttu-id="e8d0d-501">ハイブリッド接続リレーの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-501">Name of the Hybrid Connection relay.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-502">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-502">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-503">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-503">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-504">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-504">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;string&gt; ListWebAppsByHybridConnectionNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;string&gt; ListWebAppsByHybridConnectionNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebAppsByHybridConnectionNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of String)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnectionNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-505">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-505">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-506">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-506">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-507">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-507">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-508">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-508">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsByHybridConnectionNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt; ListWebAppsByHybridConnectionNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;string&gt;&gt; ListWebAppsByHybridConnectionNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsByHybridConnectionNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsByHybridConnectionNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListWebAppsByHybridConnectionNextAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-509">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-509">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-510">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-510">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-511">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-511">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-512">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-512">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-513">App Service プランのハイブリッド接続を使用するすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-513">Get all apps that use a Hybrid Connection in an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebAppsNext (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt; ListWebAppsNext(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsNext(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListWebAppsNext (operations As IAppServicePlansOperations, nextPageLink As String) As IPage(Of Site)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNext : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-514">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-514">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-515">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-515">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-516">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-516">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-517">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-517">Get all apps associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsNextAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt; ListWebAppsNextAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsNextAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListWebAppsNextAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.ListWebAppsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;ListWebAppsNextAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-518">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-518">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e8d0d-519">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-519">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-520">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-520">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-521">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-521">Get all apps associated with an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-522">App Service プランに関連付けられているすべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-522">Get all apps associated with an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootWorker">
      <MemberSignature Language="C#" Value="public static void RebootWorker (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RebootWorker(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RebootWorker(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RebootWorker (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, workerName As String)" />
      <MemberSignature Language="F#" Value="static member RebootWorker : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RebootWorker (operations, resourceGroupName, name, workerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-523">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-523">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-524">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-524">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-525">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-525">Name of the App Service plan.</span></span>
            </param>
        <param name="workerName">
            <span data-ttu-id="e8d0d-526">通常 RD. で始まるワーカー コンピューターの名前</span><span class="sxs-lookup"><span data-stu-id="e8d0d-526">Name of worker machine, which typically starts with RD.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-527">App Service プラン内のワーカーのコンピューターを再起動します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-527">Reboot a worker machine in an App Service plan.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="e8d0d-528">App Service プラン内のワーカーのコンピューターを再起動します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-528">Reboot a worker machine in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootWorkerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RebootWorkerAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RebootWorkerAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string workerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RebootWorkerAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebootWorkerAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RebootWorkerAsync (operations, resourceGroupName, name, workerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;RebootWorkerAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-529">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-529">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-530">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-530">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-531">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-531">Name of the App Service plan.</span></span>
            </param>
        <param name="workerName">
            <span data-ttu-id="e8d0d-532">通常 RD. で始まるワーカー コンピューターの名前</span><span class="sxs-lookup"><span data-stu-id="e8d0d-532">Name of worker machine, which typically starts with RD.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-533">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-533">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-534">App Service プラン内のワーカーのコンピューターを再起動します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-534">Reboot a worker machine in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-535">App Service プラン内のワーカーのコンピューターを再起動します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-535">Reboot a worker machine in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartWebApps">
      <MemberSignature Language="C#" Value="public static void RestartWebApps (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; softRestart = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void RestartWebApps(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; softRestart) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RestartWebApps(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub RestartWebApps (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, Optional softRestart As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="static member RestartWebApps : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RestartWebApps (operations, resourceGroupName, name, softRestart)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="softRestart" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-536">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-536">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-537">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-537">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-538">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-538">Name of the App Service plan.</span></span>
            </param>
        <param name="softRestart">
            <span data-ttu-id="e8d0d-539">指定&lt;コード&gt;true&lt;/code&gt;かからず、ソフト再起動、構成設定を適用し、必要に応じて、アプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-539">Specify &lt;code&gt;true&lt;/code&gt; to performa a soft restart, applies the configuration settings and restarts the apps if necessary.</span></span> <span data-ttu-id="e8d0d-540">既定値は&lt;コード&gt;false&lt;/code&gt;を常に再起動し、アプリを reprovisions</span><span class="sxs-lookup"><span data-stu-id="e8d0d-540">The default is &lt;code&gt;false&lt;/code&gt;, which always restarts and reprovisions the apps</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-541">App Service プラン内のすべてのアプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-541">Restart all apps in an App Service plan.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="e8d0d-542">App Service プラン内のすべてのアプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-542">Restart all apps in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartWebAppsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RestartWebAppsAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Nullable&lt;bool&gt; softRestart = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RestartWebAppsAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; softRestart, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RestartWebAppsAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartWebAppsAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.RestartWebAppsAsync (operations, resourceGroupName, name, softRestart, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;RestartWebAppsAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="softRestart" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-543">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-543">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-544">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-544">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-545">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-545">Name of the App Service plan.</span></span>
            </param>
        <param name="softRestart">
            <span data-ttu-id="e8d0d-546">指定&lt;コード&gt;true&lt;/code&gt;かからず、ソフト再起動、構成設定を適用し、必要に応じて、アプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-546">Specify &lt;code&gt;true&lt;/code&gt; to performa a soft restart, applies the configuration settings and restarts the apps if necessary.</span></span> <span data-ttu-id="e8d0d-547">既定値は&lt;コード&gt;false&lt;/code&gt;を常に再起動し、アプリを reprovisions</span><span class="sxs-lookup"><span data-stu-id="e8d0d-547">The default is &lt;code&gt;false&lt;/code&gt;, which always restarts and reprovisions the apps</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-548">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-548">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-549">App Service プラン内のすべてのアプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-549">Restart all apps in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-550">App Service プラン内のすべてのアプリを再起動します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-550">Restart all apps in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.AppServicePlan Update (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.AppServicePlan Update(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Update(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlan" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.Update (operations, resourceGroupName, name, appServicePlan)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.AppServicePlan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-551">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-551">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-552">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-552">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-553">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-553">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="e8d0d-554">App Service の詳細を計画します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-554">Details of the App Service plan.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-555">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-555">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-556">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-556">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; UpdateAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource appServicePlan, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt; UpdateAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource appServicePlan, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateAsync (operations, resourceGroupName, name, appServicePlan, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;UpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.WebSites.Models.AppServicePlanPatchResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-557">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-557">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-558">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-558">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-559">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-559">Name of the App Service plan.</span></span>
            </param>
        <param name="appServicePlan">
            <span data-ttu-id="e8d0d-560">App Service の詳細を計画します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-560">Details of the App Service plan.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-561">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-561">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-562">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-562">Creates or updates an App Service Plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-563">作成するか、App Service プランを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-563">Creates or updates an App Service Plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetGateway">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetGateway UpdateVnetGateway (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, Microsoft.Azure.Management.WebSites.Models.VnetGateway connectionEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetGateway UpdateVnetGateway(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, class Microsoft.Azure.Management.WebSites.Models.VnetGateway connectionEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetGateway(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateVnetGateway (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, gatewayName As String, connectionEnvelope As VnetGateway) As VnetGateway" />
      <MemberSignature Language="F#" Value="static member UpdateVnetGateway : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetGateway -&gt; Microsoft.Azure.Management.WebSites.Models.VnetGateway" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetGateway (operations, resourceGroupName, name, vnetName, gatewayName, connectionEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="connectionEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.VnetGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-564">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-564">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-565">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-565">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-566">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-566">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-567">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-567">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="e8d0d-568">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-568">Name of the gateway.</span></span> <span data-ttu-id="e8d0d-569">'Primary' のゲートウェイのみがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-569">Only the 'primary' gateway is supported.</span></span>
            </param>
        <param name="connectionEnvelope">
            <span data-ttu-id="e8d0d-570">ゲートウェイの定義です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-570">Definition of the gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-571">仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-571">Update a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-572">仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-572">Update a Virtual Network gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetGatewayAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt; UpdateVnetGatewayAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, Microsoft.Azure.Management.WebSites.Models.VnetGateway connectionEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt; UpdateVnetGatewayAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string gatewayName, class Microsoft.Azure.Management.WebSites.Models.VnetGateway connectionEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetGatewayAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateVnetGatewayAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetGatewayAsync (operations, resourceGroupName, name, vnetName, gatewayName, connectionEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;UpdateVnetGatewayAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="connectionEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.VnetGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-573">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-573">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-574">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-574">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-575">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-575">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-576">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-576">Name of the Virtual Network.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="e8d0d-577">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-577">Name of the gateway.</span></span> <span data-ttu-id="e8d0d-578">'Primary' のゲートウェイのみがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-578">Only the 'primary' gateway is supported.</span></span>
            </param>
        <param name="connectionEnvelope">
            <span data-ttu-id="e8d0d-579">ゲートウェイの定義です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-579">Definition of the gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-580">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-580">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-581">仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-581">Update a Virtual Network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-582">仮想ネットワーク ゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-582">Update a Virtual Network gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetRoute">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetRoute UpdateVnetRoute (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.WebSites.Models.VnetRoute route);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetRoute UpdateVnetRoute(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.WebSites.Models.VnetRoute route) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetRoute(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetRoute)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateVnetRoute (operations As IAppServicePlansOperations, resourceGroupName As String, name As String, vnetName As String, routeName As String, route As VnetRoute) As VnetRoute" />
      <MemberSignature Language="F#" Value="static member UpdateVnetRoute : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetRoute -&gt; Microsoft.Azure.Management.WebSites.Models.VnetRoute" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetRoute (operations, resourceGroupName, name, vnetName, routeName, route)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetRoute</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.WebSites.Models.VnetRoute" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-583">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-583">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-584">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-584">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-585">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-585">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-586">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-586">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="e8d0d-587">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-587">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="e8d0d-588">仮想ネットワーク ルートを定義します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-588">Definition of the Virtual Network route.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-589">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-589">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-590">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-590">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateVnetRouteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; UpdateVnetRouteAsync (this Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, Microsoft.Azure.Management.WebSites.Models.VnetRoute route, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; UpdateVnetRouteAsync(class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations operations, string resourceGroupName, string name, string vnetName, string routeName, class Microsoft.Azure.Management.WebSites.Models.VnetRoute route, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetRouteAsync(Microsoft.Azure.Management.WebSites.IAppServicePlansOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetRoute,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateVnetRouteAsync : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetRoute * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;" Usage="Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions.UpdateVnetRouteAsync (operations, resourceGroupName, name, vnetName, routeName, route, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.AppServicePlansOperationsExtensions/&lt;UpdateVnetRouteAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="route" Type="Microsoft.Azure.Management.WebSites.Models.VnetRoute" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e8d0d-591">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-591">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e8d0d-592">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-592">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="e8d0d-593">App Service プランの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-593">Name of the App Service plan.</span></span>
            </param>
        <param name="vnetName">
            <span data-ttu-id="e8d0d-594">仮想ネットワークの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-594">Name of the Virtual Network.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="e8d0d-595">仮想ネットワーク ルートの名前です。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-595">Name of the Virtual Network route.</span></span>
            </param>
        <param name="route">
            <span data-ttu-id="e8d0d-596">仮想ネットワーク ルートを定義します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-596">Definition of the Virtual Network route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e8d0d-597">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-597">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e8d0d-598">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-598">Create or update a Virtual Network route in an App Service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e8d0d-599">作成または、App Service プラン内の仮想ネットワーク ルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="e8d0d-599">Create or update a Virtual Network route in an App Service plan.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>