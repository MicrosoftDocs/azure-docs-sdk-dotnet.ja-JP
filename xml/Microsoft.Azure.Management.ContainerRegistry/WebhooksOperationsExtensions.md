<Type Name="WebhooksOperationsExtensions" FullName="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class WebhooksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WebhooksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WebhooksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type WebhooksOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f9565-101">WebhooksOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="f9565-101">Extension methods for WebhooksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Webhook BeginCreate (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook BeginCreate(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginCreate(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters)" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginCreate (operations, resourceGroupName, registryName, webhookName, webhookCreateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Webhook</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookCreateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-103">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-103">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-104">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-104">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-105">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-105">The name of the webhook.</span></span>
            </param>
        <param name="webhookCreateParameters">
            <span data-ttu-id="f9565-106">Webhook を作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f9565-106">The parameters for creating a webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-107">指定したパラメーターにコンテナー レジストリの webhook を作成します。</span><span class="sxs-lookup"><span data-stu-id="f9565-107">Creates a webhook for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; BeginCreateAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; BeginCreateAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, registryName, webhookName, webhookCreateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;BeginCreateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookCreateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-109">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-109">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-110">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-110">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-111">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-111">The name of the webhook.</span></span>
            </param>
        <param name="webhookCreateParameters">
            <span data-ttu-id="f9565-112">Webhook を作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f9565-112">The parameters for creating a webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-114">指定したパラメーターにコンテナー レジストリの webhook を作成します。</span><span class="sxs-lookup"><span data-stu-id="f9565-114">Creates a webhook for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginDelete (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-116">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-116">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-117">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-117">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-118">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-118">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-119">コンテナー レジストリから、webhook を削除します。</span><span class="sxs-lookup"><span data-stu-id="f9565-119">Deletes a webhook from a container registry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-121">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-121">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-122">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-122">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-123">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-123">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-125">コンテナー レジストリから、webhook を削除します。</span><span class="sxs-lookup"><span data-stu-id="f9565-125">Deletes a webhook from a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Webhook BeginUpdate (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook BeginUpdate(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginUpdate (operations, resourceGroupName, registryName, webhookName, webhookUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Webhook</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-127">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-127">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-128">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-128">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-129">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-129">The name of the webhook.</span></span>
            </param>
        <param name="webhookUpdateParameters">
            <span data-ttu-id="f9565-130">Webhook を更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f9565-130">The parameters for updating a webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-131">指定されたパラメーターで、webhook を更新します。</span><span class="sxs-lookup"><span data-stu-id="f9565-131">Updates a webhook with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; BeginUpdateAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; BeginUpdateAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, registryName, webhookName, webhookUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;BeginUpdateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-133">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-133">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-134">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-134">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-135">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-135">The name of the webhook.</span></span>
            </param>
        <param name="webhookUpdateParameters">
            <span data-ttu-id="f9565-136">Webhook を更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f9565-136">The parameters for updating a webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-138">指定されたパラメーターで、webhook を更新します。</span><span class="sxs-lookup"><span data-stu-id="f9565-138">Updates a webhook with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Create (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Create(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Create(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Create (operations, resourceGroupName, registryName, webhookName, webhookCreateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Webhook</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookCreateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-140">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-140">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-141">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-141">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-142">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-142">The name of the webhook.</span></span>
            </param>
        <param name="webhookCreateParameters">
            <span data-ttu-id="f9565-143">Webhook を作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f9565-143">The parameters for creating a webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-144">指定したパラメーターにコンテナー レジストリの webhook を作成します。</span><span class="sxs-lookup"><span data-stu-id="f9565-144">Creates a webhook for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; CreateAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; CreateAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.CreateAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.CreateAsync (operations, resourceGroupName, registryName, webhookName, webhookCreateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookCreateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-146">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-146">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-147">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-147">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-148">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-148">The name of the webhook.</span></span>
            </param>
        <param name="webhookCreateParameters">
            <span data-ttu-id="f9565-149">Webhook を作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f9565-149">The parameters for creating a webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-151">指定したパラメーターにコンテナー レジストリの webhook を作成します。</span><span class="sxs-lookup"><span data-stu-id="f9565-151">Creates a webhook for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Delete(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Delete (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-153">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-153">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-154">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-154">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-155">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-155">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-156">コンテナー レジストリから、webhook を削除します。</span><span class="sxs-lookup"><span data-stu-id="f9565-156">Deletes a webhook from a container registry.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.DeleteAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-158">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-158">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-159">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-159">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-160">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-160">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-162">コンテナー レジストリから、webhook を削除します。</span><span class="sxs-lookup"><span data-stu-id="f9565-162">Deletes a webhook from a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Get (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Get(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Get(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String) As Webhook" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Get (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Webhook</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-164">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-164">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-165">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-165">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-166">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-166">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-167">指定の webhook のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="f9565-167">Gets the properties of the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; GetAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; GetAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-169">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-169">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-170">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-170">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-171">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-171">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-173">指定の webhook のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="f9565-173">Gets the properties of the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCallbackConfig">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig GetCallbackConfig (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig GetCallbackConfig(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetCallbackConfig(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCallbackConfig (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String) As CallbackConfig" />
      <MemberSignature Language="F#" Value="static member GetCallbackConfig : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetCallbackConfig (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-174">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-175">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-175">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-176">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-176">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-177">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-177">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-178">Webhook の URI をサービスの構成とカスタム ヘッダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="f9565-178">Gets the configuration of service URI and custom headers for the webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCallbackConfigAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt; GetCallbackConfigAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt; GetCallbackConfigAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetCallbackConfigAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCallbackConfigAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.GetCallbackConfigAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;GetCallbackConfigAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-180">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-180">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-181">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-181">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-182">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-182">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-184">Webhook の URI をサービスの構成とカスタム ヘッダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="f9565-184">Gets the configuration of service URI and custom headers for the webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; List (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; List(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.List(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IWebhooksOperations, resourceGroupName As String, registryName As String) As IPage(Of Webhook)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.List (operations, resourceGroupName, registryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-185">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-186">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-186">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-187">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-187">The name of the container registry.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-188">指定したコンテナー レジストリに対するすべての webhook を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f9565-188">Lists all the webhooks for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; ListAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; ListAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListAsync (operations, resourceGroupName, registryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-189">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-190">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-190">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-191">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-191">The name of the container registry.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-193">指定したコンテナー レジストリに対するすべての webhook を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f9565-193">Lists all the webhooks for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEvents">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt; ListEvents (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt; ListEvents(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEvents(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEvents (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String) As IPage(Of EventModel)" />
      <MemberSignature Language="F#" Value="static member ListEvents : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEvents (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-195">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-195">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-196">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-196">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-197">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-197">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-198">指定の webhook の最近のイベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f9565-198">Lists recent events for the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt; ListEventsAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt; ListEventsAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventsAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;ListEventsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-199">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-200">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-200">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-201">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-201">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-202">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-202">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-204">指定の webhook の最近のイベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f9565-204">Lists recent events for the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt; ListEventsNext (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt; ListEventsNext(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsNext(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListEventsNext (operations As IWebhooksOperations, nextPageLink As String) As IPage(Of EventModel)" />
      <MemberSignature Language="F#" Value="static member ListEventsNext : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f9565-206">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f9565-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-207">指定の webhook の最近のイベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f9565-207">Lists recent events for the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEventsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt; ListEventsNextAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt; ListEventsNextAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsNextAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEventsNextAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListEventsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;ListEventsNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-208">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f9565-209">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f9565-209">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-210">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-211">指定の webhook の最近のイベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f9565-211">Lists recent events for the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; ListNext (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; ListNext(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListNext(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IWebhooksOperations, nextPageLink As String) As IPage(Of Webhook)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-212">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-212">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f9565-213">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f9565-213">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-214">指定したコンテナー レジストリに対するすべての webhook を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f9565-214">Lists all the webhooks for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;ListNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-215">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="f9565-216">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f9565-216">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-218">指定したコンテナー レジストリに対するすべての webhook を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="f9565-218">Lists all the webhooks for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ping">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo Ping (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo Ping(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Ping(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Ping (operations As IWebhooksOperations, resourceGroupName As String, registryName As String, webhookName As String) As EventInfo" />
      <MemberSignature Language="F#" Value="static member Ping : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Ping (operations, resourceGroupName, registryName, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-219">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-219">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-220">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-220">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-221">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-221">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-222">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-222">The name of the webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-223">Webhook に送信される ping のイベントをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="f9565-223">Triggers a ping event to be sent to the webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt; PingAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt; PingAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.PingAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PingAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.PingAsync (operations, resourceGroupName, registryName, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;PingAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-224">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-224">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-225">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-225">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-226">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-226">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-227">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-227">The name of the webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-228">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-229">Webhook に送信される ping のイベントをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="f9565-229">Triggers a ping event to be sent to the webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Update (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook Update(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Update(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Webhook" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.Update (operations, resourceGroupName, registryName, webhookName, webhookUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Webhook</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-230">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-230">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-231">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-231">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-232">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-232">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-233">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-233">The name of the webhook.</span></span>
            </param>
        <param name="webhookUpdateParameters">
            <span data-ttu-id="f9565-234">Webhook を更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f9565-234">The parameters for updating a webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-235">指定されたパラメーターで、webhook を更新します。</span><span class="sxs-lookup"><span data-stu-id="f9565-235">Updates a webhook with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; UpdateAsync (this Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt; UpdateAsync(class Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations operations, string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations * string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions.UpdateAsync (operations, resourceGroupName, registryName, webhookName, webhookUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ContainerRegistry.WebhooksOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f9565-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="f9565-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f9565-237">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-237">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="f9565-238">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-238">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="f9565-239">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="f9565-239">The name of the webhook.</span></span>
            </param>
        <param name="webhookUpdateParameters">
            <span data-ttu-id="f9565-240">Webhook を更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f9565-240">The parameters for updating a webhook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9565-241">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9565-241">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9565-242">指定されたパラメーターで、webhook を更新します。</span><span class="sxs-lookup"><span data-stu-id="f9565-242">Updates a webhook with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>