<Type Name="EventSubscriptionsOperationsExtensions" FullName="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EventSubscriptionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EventSubscriptionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EventSubscriptionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EventSubscriptionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1c5a1-101">EventSubscriptionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-101">Extension methods for EventSubscriptionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginCreate (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginCreate(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String, eventSubscriptionInfo As EventSubscription) As EventSubscription" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreate (operations, scope, eventSubscriptionName, eventSubscriptionInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-103">イベント サブスクリプションを作成する必要とするリソースのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-103">The scope of the resource to which the event subscription needs to be created.</span></span> <span data-ttu-id="1c5a1-104">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-104">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-105">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-105">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-106">イベント サブスクリプションを作成するの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-106">Name of the event subscription to be created.</span></span> <span data-ttu-id="1c5a1-107">イベント サブスクリプション名は、3 ~ 64 文字以下でなければし、英数字文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-107">Event subscription names must be between 3 and 64 characters in length and use alphanumeric letters only.</span></span>
            </param>
        <param name="eventSubscriptionInfo">
            <span data-ttu-id="1c5a1-108">移行先とフィルター情報を含むイベント サブスクリプションのプロパティ</span><span class="sxs-lookup"><span data-stu-id="1c5a1-108">Event subscription properties containing the destination and filter information</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-109">イベント サブスクリプションを作成します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-109">Create an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-110">指定されたスコープに新しいイベント サブスクリプションを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-110">Asynchronously creates a new event subscription to the specified scope.</span></span>
            <span data-ttu-id="1c5a1-111">既存のサブスクリプションのイベントは、この API で更新することはできず、イベント サブスクリプションの更新 API を代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-111">Existing event subscriptions cannot be updated with this API and should instead use the Update event subscription API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginCreateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginCreateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreateAsync (operations, scope, eventSubscriptionName, eventSubscriptionInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;BeginCreateAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-112">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-113">イベント サブスクリプションを作成する必要とするリソースのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-113">The scope of the resource to which the event subscription needs to be created.</span></span> <span data-ttu-id="1c5a1-114">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-114">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-115">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-115">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-116">イベント サブスクリプションを作成するの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-116">Name of the event subscription to be created.</span></span> <span data-ttu-id="1c5a1-117">イベント サブスクリプション名は、3 ~ 64 文字以下でなければし、英数字文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-117">Event subscription names must be between 3 and 64 characters in length and use alphanumeric letters only.</span></span>
            </param>
        <param name="eventSubscriptionInfo">
            <span data-ttu-id="1c5a1-118">移行先とフィルター情報を含むイベント サブスクリプションのプロパティ</span><span class="sxs-lookup"><span data-stu-id="1c5a1-118">Event subscription properties containing the destination and filter information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-120">イベント サブスクリプションを作成します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-120">Create an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-121">指定されたスコープに新しいイベント サブスクリプションを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-121">Asynchronously creates a new event subscription to the specified scope.</span></span>
            <span data-ttu-id="1c5a1-122">既存のサブスクリプションのイベントは、この API で更新することはできず、イベント サブスクリプションの更新 API を代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-122">Existing event subscriptions cannot be updated with this API and should instead use the Update event subscription API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDelete (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-123">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-124">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-124">The scope of the event subscription.</span></span> <span data-ttu-id="1c5a1-125">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-125">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-126">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-126">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-127">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-127">Name of the event subscription</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-128">イベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-128">Delete an event subscription</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1c5a1-129">既存のイベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-129">Delete an existing event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDeleteAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-130">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-131">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-131">The scope of the event subscription.</span></span> <span data-ttu-id="1c5a1-132">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-132">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-133">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-133">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-134">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-134">Name of the event subscription</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-136">イベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-136">Delete an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-137">既存のイベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-137">Delete an existing event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginUpdate (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginUpdate(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdate (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-138">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-139">既存のイベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-139">The scope of existing event subscription.</span></span> <span data-ttu-id="1c5a1-140">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-140">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-141">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-141">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-142">イベント サブスクリプションを作成するの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-142">Name of the event subscription to be created</span></span>
            </param>
        <param name="eventSubscriptionUpdateParameters">
            <span data-ttu-id="1c5a1-143">サブスクリプションの更新されたイベント情報</span><span class="sxs-lookup"><span data-stu-id="1c5a1-143">Updated event subscription information</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-144">イベント サブスクリプションを更新します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-144">Update an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-145">既存のイベント サブスクリプションを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-145">Asynchronously updates an existing event subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginUpdateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginUpdateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdateAsync (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-146">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-147">既存のイベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-147">The scope of existing event subscription.</span></span> <span data-ttu-id="1c5a1-148">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-148">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-149">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-149">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-150">イベント サブスクリプションを作成するの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-150">Name of the event subscription to be created</span></span>
            </param>
        <param name="eventSubscriptionUpdateParameters">
            <span data-ttu-id="1c5a1-151">サブスクリプションの更新されたイベント情報</span><span class="sxs-lookup"><span data-stu-id="1c5a1-151">Updated event subscription information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-153">イベント サブスクリプションを更新します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-153">Update an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-154">既存のイベント サブスクリプションを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-154">Asynchronously updates an existing event subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription Create (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription Create(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Create(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String, eventSubscriptionInfo As EventSubscription) As EventSubscription" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Create (operations, scope, eventSubscriptionName, eventSubscriptionInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-155">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-156">イベント サブスクリプションを作成する必要とするリソースのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-156">The scope of the resource to which the event subscription needs to be created.</span></span> <span data-ttu-id="1c5a1-157">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-157">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-158">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-158">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-159">イベント サブスクリプションを作成するの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-159">Name of the event subscription to be created.</span></span> <span data-ttu-id="1c5a1-160">イベント サブスクリプション名は、3 ~ 64 文字以下でなければし、英数字文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-160">Event subscription names must be between 3 and 64 characters in length and use alphanumeric letters only.</span></span>
            </param>
        <param name="eventSubscriptionInfo">
            <span data-ttu-id="1c5a1-161">移行先とフィルター情報を含むイベント サブスクリプションのプロパティ</span><span class="sxs-lookup"><span data-stu-id="1c5a1-161">Event subscription properties containing the destination and filter information</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-162">イベント サブスクリプションを作成します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-162">Create an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-163">指定されたスコープに新しいイベント サブスクリプションを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-163">Asynchronously creates a new event subscription to the specified scope.</span></span>
            <span data-ttu-id="1c5a1-164">既存のサブスクリプションのイベントは、この API で更新することはできず、イベント サブスクリプションの更新 API を代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-164">Existing event subscriptions cannot be updated with this API and should instead use the Update event subscription API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; CreateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; CreateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.CreateAsync (operations, scope, eventSubscriptionName, eventSubscriptionInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-165">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-166">イベント サブスクリプションを作成する必要とするリソースのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-166">The scope of the resource to which the event subscription needs to be created.</span></span> <span data-ttu-id="1c5a1-167">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-167">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-168">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-168">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-169">イベント サブスクリプションを作成するの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-169">Name of the event subscription to be created.</span></span> <span data-ttu-id="1c5a1-170">イベント サブスクリプション名は、3 ~ 64 文字以下でなければし、英数字文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-170">Event subscription names must be between 3 and 64 characters in length and use alphanumeric letters only.</span></span>
            </param>
        <param name="eventSubscriptionInfo">
            <span data-ttu-id="1c5a1-171">移行先とフィルター情報を含むイベント サブスクリプションのプロパティ</span><span class="sxs-lookup"><span data-stu-id="1c5a1-171">Event subscription properties containing the destination and filter information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-173">イベント サブスクリプションを作成します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-173">Create an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-174">指定されたスコープに新しいイベント サブスクリプションを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-174">Asynchronously creates a new event subscription to the specified scope.</span></span>
            <span data-ttu-id="1c5a1-175">既存のサブスクリプションのイベントは、この API で更新することはできず、イベント サブスクリプションの更新 API を代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-175">Existing event subscriptions cannot be updated with this API and should instead use the Update event subscription API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Delete(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Delete (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-176">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-177">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-177">The scope of the event subscription.</span></span> <span data-ttu-id="1c5a1-178">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-178">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-179">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-179">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-180">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-180">Name of the event subscription</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-181">イベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-181">Delete an event subscription</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="1c5a1-182">既存のイベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-182">Delete an existing event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.DeleteAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-183">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-184">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-184">The scope of the event subscription.</span></span> <span data-ttu-id="1c5a1-185">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-185">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-186">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-186">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-187">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-187">Name of the event subscription</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-189">イベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-189">Delete an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-190">既存のイベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-190">Delete an existing event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription Get (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription Get(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Get(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String) As EventSubscription" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Get (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-191">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-192">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-192">The scope of the event subscription.</span></span> <span data-ttu-id="1c5a1-193">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-193">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-194">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-194">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-195">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-195">Name of the event subscription</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-196">イベント サブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-196">Get an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-197">イベント サブスクリプションのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-197">Get properties of an event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; GetAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; GetAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-198">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-199">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-199">The scope of the event subscription.</span></span> <span data-ttu-id="1c5a1-200">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-200">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-201">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-201">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-202">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-202">Name of the event subscription</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-204">イベント サブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-204">Get an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-205">イベント サブスクリプションのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-205">Get properties of an event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFullUrl">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl GetFullUrl (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl GetFullUrl(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrl(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetFullUrl (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String) As EventSubscriptionFullUrl" />
      <MemberSignature Language="F#" Value="static member GetFullUrl : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrl (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-206">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-206">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-207">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-207">The scope of the event subscription.</span></span> <span data-ttu-id="1c5a1-208">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-208">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-209">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-209">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-210">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-210">Name of the event subscription</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-211">イベント サブスクリプションの完全な URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-211">Get full URL of an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-212">イベント サブスクリプションの完全なエンドポイント URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-212">Get the full endpoint URL for an event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFullUrlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt; GetFullUrlAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt; GetFullUrlAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrlAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFullUrlAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrlAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;GetFullUrlAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-213">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-213">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-214">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-214">The scope of the event subscription.</span></span> <span data-ttu-id="1c5a1-215">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-215">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-216">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-216">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-217">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-217">Name of the event subscription</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-219">イベント サブスクリプションの完全な URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-219">Get full URL of an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-220">イベント サブスクリプションの完全なエンドポイント URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-220">Get the full endpoint URL for an event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResource">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListByResource (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListByResource(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResource(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResource (operations As IEventSubscriptionsOperations, resourceGroupName As String, providerNamespace As String, resourceTypeName As String, resourceName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListByResource : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResource (operations, resourceGroupName, providerNamespace, resourceTypeName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c5a1-222">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-222">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="providerNamespace">
            <span data-ttu-id="1c5a1-223">トピックのプロバイダーの Namespace</span><span class="sxs-lookup"><span data-stu-id="1c5a1-223">Namespace of the provider of the topic</span></span>
            </param>
        <param name="resourceTypeName">
            <span data-ttu-id="1c5a1-224">リソースの種類の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-224">Name of the resource type</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="1c5a1-225">リソースの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-225">Name of the resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-226">特定のトピックのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-226">List all event subscriptions for a specific topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-227">特定のトピック用に作成されたすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-227">List all event subscriptions that have been created for a specific topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListByResourceAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListByResourceAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResourceAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResourceAsync (operations, resourceGroupName, providerNamespace, resourceTypeName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListByResourceAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-228">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-228">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c5a1-229">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-229">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="providerNamespace">
            <span data-ttu-id="1c5a1-230">トピックのプロバイダーの Namespace</span><span class="sxs-lookup"><span data-stu-id="1c5a1-230">Namespace of the provider of the topic</span></span>
            </param>
        <param name="resourceTypeName">
            <span data-ttu-id="1c5a1-231">リソースの種類の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-231">Name of the resource type</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="1c5a1-232">リソースの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-232">Name of the resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-233">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-233">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-234">特定のトピックのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-234">List all event subscriptions for a specific topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-235">特定のトピック用に作成されたすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-235">List all event subscriptions that have been created for a specific topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroup (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroup(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroup(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalByResourceGroup (operations As IEventSubscriptionsOperations, resourceGroupName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroup : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-236">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c5a1-237">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-237">The name of the resource group within the user's subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-238">Azure のサブスクリプションとリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-238">List all global event subscriptions under an Azure subscription and resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-239">特定の Azure サブスクリプションとリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-239">List all global event subscriptions under a specific Azure subscription and resource group</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroupAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalByResourceGroupAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-240">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c5a1-241">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-241">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-242">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-242">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-243">Azure のサブスクリプションとリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-243">List all global event subscriptions under an Azure subscription and resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-244">特定の Azure サブスクリプションとリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-244">List all global event subscriptions under a specific Azure subscription and resource group</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroupForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroupForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalByResourceGroupForTopicType (operations As IEventSubscriptionsOperations, resourceGroupName As String, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroupForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicType (operations, resourceGroupName, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-245">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-245">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c5a1-246">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-246">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="1c5a1-247">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-247">Name of the topic type</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-248">トピックの種類のリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-248">List all global event subscriptions under a resource group for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-249">特定のトピックの種類のリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-249">List all global event subscriptions under a resource group for a specific topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroupForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicTypeAsync (operations, resourceGroupName, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalByResourceGroupForTopicTypeAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-250">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-250">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c5a1-251">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-251">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="1c5a1-252">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-252">Name of the topic type</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-253">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-254">トピックの種類のリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-254">List all global event subscriptions under a resource group for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-255">特定のトピックの種類のリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-255">List all global event subscriptions under a resource group for a specific topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscription">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscription (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscription(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscription(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalBySubscription (operations As IEventSubscriptionsOperations) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscription : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscription operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-256">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-256">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-257">Azure サブスクリプションの下のすべてのグローバル イベント サブスクリプションの集計の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-257">Get an aggregated list of all global event subscriptions under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-258">特定の Azure サブスクリプションの下のすべての集計のグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-258">List all aggregated global event subscriptions under a specific Azure subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscriptionAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalBySubscriptionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-259">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-259">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-260">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-260">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-261">Azure サブスクリプションの下のすべてのグローバル イベント サブスクリプションの集計の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-261">Get an aggregated list of all global event subscriptions under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-262">特定の Azure サブスクリプションの下のすべての集計のグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-262">List all aggregated global event subscriptions under a specific Azure subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscriptionForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscriptionForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalBySubscriptionForTopicType (operations As IEventSubscriptionsOperations, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscriptionForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicType (operations, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-263">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-263">The operations group for this extension method.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="1c5a1-264">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-264">Name of the topic type</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-265">トピックの種類のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-265">List all global event subscriptions for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-266">トピックの種類の Azure サブスクリプションの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-266">List all global event subscriptions under an Azure subscription for a topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscriptionForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicTypeAsync (operations, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalBySubscriptionForTopicTypeAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-267">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-267">The operations group for this extension method.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="1c5a1-268">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-268">Name of the topic type</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-270">トピックの種類のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-270">List all global event subscriptions for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-271">トピックの種類の Azure サブスクリプションの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-271">List all global event subscriptions under an Azure subscription for a topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroup (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroup(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroup(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalByResourceGroup (operations As IEventSubscriptionsOperations, resourceGroupName As String, location As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroup : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroup (operations, resourceGroupName, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-272">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-272">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c5a1-273">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-273">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="1c5a1-274">場所の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-274">Name of the location</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-275">Azure のサブスクリプションとリソース グループの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-275">List all regional event subscriptions under an Azure subscription and resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-276">特定の Azure サブスクリプションとリソース グループの下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-276">List all event subscriptions from the given location under a specific Azure subscription and resource group</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroupAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupAsync (operations, resourceGroupName, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalByResourceGroupAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-277">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-277">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c5a1-278">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-278">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="1c5a1-279">場所の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-279">Name of the location</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-280">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-280">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-281">Azure のサブスクリプションとリソース グループの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-281">List all regional event subscriptions under an Azure subscription and resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-282">特定の Azure サブスクリプションとリソース グループの下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-282">List all event subscriptions from the given location under a specific Azure subscription and resource group</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroupForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroupForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalByResourceGroupForTopicType (operations As IEventSubscriptionsOperations, resourceGroupName As String, location As String, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroupForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicType (operations, resourceGroupName, location, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-283">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-283">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c5a1-284">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-284">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="1c5a1-285">場所の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-285">Name of the location</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="1c5a1-286">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-286">Name of the topic type</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-287">トピックの種類の Azure サブスクリプションとリソース グループの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-287">List all regional event subscriptions under an Azure subscription and resource group for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-288">特定 Azure サブスクリプションとリソース グループとトピックの種類の下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-288">List all event subscriptions from the given location under a specific Azure subscription and resource group and topic type</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroupForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicTypeAsync (operations, resourceGroupName, location, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalByResourceGroupForTopicTypeAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-289">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-289">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c5a1-290">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-290">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="1c5a1-291">場所の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-291">Name of the location</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="1c5a1-292">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-292">Name of the topic type</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-293">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-293">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-294">トピックの種類の Azure サブスクリプションとリソース グループの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-294">List all regional event subscriptions under an Azure subscription and resource group for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-295">特定 Azure サブスクリプションとリソース グループとトピックの種類の下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-295">List all event subscriptions from the given location under a specific Azure subscription and resource group and topic type</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscription">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscription (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscription(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscription(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalBySubscription (operations As IEventSubscriptionsOperations, location As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscription : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscription (operations, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-296">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-296">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="1c5a1-297">場所の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-297">Name of the location</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-298">Azure サブスクリプションの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-298">List all regional event subscriptions under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-299">特定の Azure サブスクリプションの下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-299">List all event subscriptions from the given location under a specific Azure subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscriptionAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalBySubscriptionAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-300">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-300">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="1c5a1-301">場所の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-301">Name of the location</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-302">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-302">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-303">Azure サブスクリプションの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-303">List all regional event subscriptions under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-304">特定の Azure サブスクリプションの下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-304">List all event subscriptions from the given location under a specific Azure subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscriptionForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscriptionForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalBySubscriptionForTopicType (operations As IEventSubscriptionsOperations, location As String, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscriptionForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicType (operations, location, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-305">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-305">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="1c5a1-306">場所の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-306">Name of the location</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="1c5a1-307">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-307">Name of the topic type</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-308">トピックの種類の Azure サブスクリプションの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-308">List all regional event subscriptions under an Azure subscription for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-309">特定の Azure サブスクリプションとトピック種類の指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-309">List all event subscriptions from the given location under a specific Azure subscription and topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscriptionForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicTypeAsync (operations, location, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalBySubscriptionForTopicTypeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-310">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-310">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="1c5a1-311">場所の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-311">Name of the location</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="1c5a1-312">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-312">Name of the topic type</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-313">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-313">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-314">トピックの種類の Azure サブスクリプションの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-314">List all regional event subscriptions under an Azure subscription for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-315">特定の Azure サブスクリプションとトピック種類の指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-315">List all event subscriptions from the given location under a specific Azure subscription and topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription Update (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription Update(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Update(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Update (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-316">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-316">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-317">既存のイベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-317">The scope of existing event subscription.</span></span> <span data-ttu-id="1c5a1-318">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-318">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-319">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-319">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-320">イベント サブスクリプションを作成するの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-320">Name of the event subscription to be created</span></span>
            </param>
        <param name="eventSubscriptionUpdateParameters">
            <span data-ttu-id="1c5a1-321">サブスクリプションの更新されたイベント情報</span><span class="sxs-lookup"><span data-stu-id="1c5a1-321">Updated event subscription information</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-322">イベント サブスクリプションを更新します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-322">Update an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-323">既存のイベント サブスクリプションを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-323">Asynchronously updates an existing event subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; UpdateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; UpdateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.UpdateAsync (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c5a1-324">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-324">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="1c5a1-325">既存のイベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-325">The scope of existing event subscription.</span></span> <span data-ttu-id="1c5a1-326">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-326">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="1c5a1-327">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-327">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="1c5a1-328">イベント サブスクリプションを作成するの名前</span><span class="sxs-lookup"><span data-stu-id="1c5a1-328">Name of the event subscription to be created</span></span>
            </param>
        <param name="eventSubscriptionUpdateParameters">
            <span data-ttu-id="1c5a1-329">サブスクリプションの更新されたイベント情報</span><span class="sxs-lookup"><span data-stu-id="1c5a1-329">Updated event subscription information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c5a1-330">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-330">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c5a1-331">イベント サブスクリプションを更新します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-331">Update an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1c5a1-332">既存のイベント サブスクリプションを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="1c5a1-332">Asynchronously updates an existing event subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>