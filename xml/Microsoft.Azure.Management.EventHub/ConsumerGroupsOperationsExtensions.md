<Type Name="ConsumerGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ConsumerGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ConsumerGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ConsumerGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ConsumerGroupsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2b295-101">ConsumerGroupsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="2b295-101">Extension methods for ConsumerGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.ConsumerGroup CreateOrUpdate (this Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, Microsoft.Azure.Management.EventHub.Models.ConsumerGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup CreateOrUpdate(class Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.ConsumerGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IConsumerGroupsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String, consumerGroupName As String, parameters As ConsumerGroup) As ConsumerGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations * string * string * string * string * Microsoft.Azure.Management.EventHub.Models.ConsumerGroup -&gt; Microsoft.Azure.Management.EventHub.Models.ConsumerGroup" Usage="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, eventHubName, consumerGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.ConsumerGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2b295-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2b295-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2b295-103">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="2b295-103">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2b295-104">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="2b295-104">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2b295-105">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="2b295-105">The Event Hub name</span></span>
            </param>
        <param name="consumerGroupName">
            <span data-ttu-id="2b295-106">コンシューマー グループ名</span><span class="sxs-lookup"><span data-stu-id="2b295-106">The consumer group name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2b295-107">作成またはコンシューマー グループ リソースの更新に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="2b295-107">Parameters supplied to create or update a consumer group resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b295-108">作成するか、Namespace 内で入れ子になったリソースとして、イベント ハブ コンシューマー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="2b295-108">Creates or updates an Event Hubs consumer group as a nested resource within a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, Microsoft.Azure.Management.EventHub.Models.ConsumerGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.ConsumerGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations * string * string * string * string * Microsoft.Azure.Management.EventHub.Models.ConsumerGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;" Usage="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, eventHubName, consumerGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2b295-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2b295-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2b295-110">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="2b295-110">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2b295-111">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="2b295-111">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2b295-112">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="2b295-112">The Event Hub name</span></span>
            </param>
        <param name="consumerGroupName">
            <span data-ttu-id="2b295-113">コンシューマー グループ名</span><span class="sxs-lookup"><span data-stu-id="2b295-113">The consumer group name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2b295-114">作成またはコンシューマー グループ リソースの更新に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="2b295-114">Parameters supplied to create or update a consumer group resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2b295-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2b295-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b295-116">作成するか、Namespace 内で入れ子になったリソースとして、イベント ハブ コンシューマー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="2b295-116">Creates or updates an Event Hubs consumer group as a nested resource within a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IConsumerGroupsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String, consumerGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, eventHubName, consumerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2b295-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2b295-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2b295-118">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="2b295-118">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2b295-119">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="2b295-119">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2b295-120">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="2b295-120">The Event Hub name</span></span>
            </param>
        <param name="consumerGroupName">
            <span data-ttu-id="2b295-121">コンシューマー グループ名</span><span class="sxs-lookup"><span data-stu-id="2b295-121">The consumer group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b295-122">指定されたイベント ハブとリソース グループからのコンシューマー グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="2b295-122">Deletes a consumer group from the specified Event Hub and resource group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, eventHubName, consumerGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2b295-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2b295-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2b295-124">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="2b295-124">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2b295-125">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="2b295-125">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2b295-126">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="2b295-126">The Event Hub name</span></span>
            </param>
        <param name="consumerGroupName">
            <span data-ttu-id="2b295-127">コンシューマー グループ名</span><span class="sxs-lookup"><span data-stu-id="2b295-127">The consumer group name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2b295-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2b295-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b295-129">指定されたイベント ハブとリソース グループからのコンシューマー グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="2b295-129">Deletes a consumer group from the specified Event Hub and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventHub.Models.ConsumerGroup Get (this Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup Get(class Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.Get(Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IConsumerGroupsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String, consumerGroupName As String) As ConsumerGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.ConsumerGroup" Usage="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.Get (operations, resourceGroupName, namespaceName, eventHubName, consumerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.ConsumerGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2b295-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2b295-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2b295-131">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="2b295-131">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2b295-132">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="2b295-132">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2b295-133">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="2b295-133">The Event Hub name</span></span>
            </param>
        <param name="consumerGroupName">
            <span data-ttu-id="2b295-134">コンシューマー グループ名</span><span class="sxs-lookup"><span data-stu-id="2b295-134">The consumer group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b295-135">指定されたコンシューマー グループの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b295-135">Gets a description for the specified consumer group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt; GetAsync (this Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt; GetAsync(class Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;" Usage="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, eventHubName, consumerGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2b295-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2b295-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2b295-137">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="2b295-137">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2b295-138">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="2b295-138">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2b295-139">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="2b295-139">The Event Hub name</span></span>
            </param>
        <param name="consumerGroupName">
            <span data-ttu-id="2b295-140">コンシューマー グループ名</span><span class="sxs-lookup"><span data-stu-id="2b295-140">The consumer group name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2b295-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2b295-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b295-142">指定されたコンシューマー グループの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b295-142">Gets a description for the specified consumer group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEventHub">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt; ListByEventHub (this Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt; ListByEventHub(class Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.ListByEventHub(Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByEventHub (operations As IConsumerGroupsOperations, resourceGroupName As String, namespaceName As String, eventHubName As String) As IPage(Of ConsumerGroup)" />
      <MemberSignature Language="F#" Value="static member ListByEventHub : Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;" Usage="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.ListByEventHub (operations, resourceGroupName, namespaceName, eventHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2b295-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2b295-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2b295-144">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="2b295-144">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2b295-145">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="2b295-145">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2b295-146">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="2b295-146">The Event Hub name</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b295-147">Namespace 内のすべてのコンシューマー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="2b295-147">Gets all the consumer groups in a Namespace.</span></span> <span data-ttu-id="2b295-148">Namespace にコンシューマー グループが存在しない場合は、空のフィードが返されます。</span><span class="sxs-lookup"><span data-stu-id="2b295-148">An empty feed is returned if no consumer group exists in the Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEventHubAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt; ListByEventHubAsync (this Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt; ListByEventHubAsync(class Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string resourceGroupName, string namespaceName, string eventHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.ListByEventHubAsync(Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEventHubAsync : Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.ListByEventHubAsync (operations, resourceGroupName, namespaceName, eventHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions/&lt;ListByEventHubAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2b295-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2b295-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2b295-150">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="2b295-150">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="2b295-151">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="2b295-151">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="2b295-152">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="2b295-152">The Event Hub name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2b295-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2b295-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b295-154">Namespace 内のすべてのコンシューマー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="2b295-154">Gets all the consumer groups in a Namespace.</span></span> <span data-ttu-id="2b295-155">Namespace にコンシューマー グループが存在しない場合は、空のフィードが返されます。</span><span class="sxs-lookup"><span data-stu-id="2b295-155">An empty feed is returned if no consumer group exists in the Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEventHubNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt; ListByEventHubNext (this Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt; ListByEventHubNext(class Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.ListByEventHubNext(Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByEventHubNext (operations As IConsumerGroupsOperations, nextPageLink As String) As IPage(Of ConsumerGroup)" />
      <MemberSignature Language="F#" Value="static member ListByEventHubNext : Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;" Usage="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.ListByEventHubNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2b295-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2b295-156">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2b295-157">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="2b295-157">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b295-158">Namespace 内のすべてのコンシューマー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="2b295-158">Gets all the consumer groups in a Namespace.</span></span> <span data-ttu-id="2b295-159">Namespace にコンシューマー グループが存在しない場合は、空のフィードが返されます。</span><span class="sxs-lookup"><span data-stu-id="2b295-159">An empty feed is returned if no consumer group exists in the Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEventHubNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt; ListByEventHubNextAsync (this Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt; ListByEventHubNextAsync(class Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.ListByEventHubNextAsync(Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEventHubNextAsync : Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;" Usage="Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions.ListByEventHubNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventHub.ConsumerGroupsOperationsExtensions/&lt;ListByEventHubNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2b295-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2b295-160">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2b295-161">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="2b295-161">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2b295-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2b295-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2b295-163">Namespace 内のすべてのコンシューマー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="2b295-163">Gets all the consumer groups in a Namespace.</span></span> <span data-ttu-id="2b295-164">Namespace にコンシューマー グループが存在しない場合は、空のフィードが返されます。</span><span class="sxs-lookup"><span data-stu-id="2b295-164">An empty feed is returned if no consumer group exists in the Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>