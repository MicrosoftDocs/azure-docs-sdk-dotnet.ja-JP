<Type Name="SubscriptionsOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubscriptionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubscriptionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubscriptionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubscriptionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="575f2-101">SubscriptionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="575f2-101">Extension methods for SubscriptionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="575f2-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="575f2-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="575f2-103">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="575f2-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="575f2-104">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="575f2-104">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="575f2-105">トピック名。</span><span class="sxs-lookup"><span data-stu-id="575f2-105">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="575f2-106">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="575f2-106">The subscription name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="575f2-107">サブスクリプション リソースを作成する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="575f2-107">Parameters supplied to create a subscription resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="575f2-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="575f2-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="575f2-109">トピック サブスクリプションを作成します。</span><span class="sxs-lookup"><span data-stu-id="575f2-109">Creates a topic subscription.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639385.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="575f2-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="575f2-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="575f2-111">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="575f2-111">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="575f2-112">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="575f2-112">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="575f2-113">トピック名。</span><span class="sxs-lookup"><span data-stu-id="575f2-113">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="575f2-114">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="575f2-114">The subscription name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="575f2-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="575f2-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="575f2-116">指定したトピックからサブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="575f2-116">Deletes a subscription from the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639381.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="575f2-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="575f2-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="575f2-118">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="575f2-118">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="575f2-119">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="575f2-119">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="575f2-120">トピック名。</span><span class="sxs-lookup"><span data-stu-id="575f2-120">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="575f2-121">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="575f2-121">The subscription name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="575f2-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="575f2-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="575f2-123">指定したトピックのサブスクリプションの説明を返します。</span><span class="sxs-lookup"><span data-stu-id="575f2-123">Returns a subscription description for the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639402.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopicAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt; ListByTopicAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt; ListByTopicAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.ListByTopicAsync(Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTopicAsync : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.ListByTopicAsync (operations, resourceGroupName, namespaceName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions/&lt;ListByTopicAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="575f2-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="575f2-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="575f2-125">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="575f2-125">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="575f2-126">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="575f2-126">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="575f2-127">トピック名。</span><span class="sxs-lookup"><span data-stu-id="575f2-127">The topic name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="575f2-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="575f2-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="575f2-129">指定したトピックの下のすべてのサブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="575f2-129">List all the subscriptions under a specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopicNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt; ListByTopicNextAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt; ListByTopicNextAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.ListByTopicNextAsync(Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTopicNextAsync : Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions.ListByTopicNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.SubscriptionsOperationsExtensions/&lt;ListByTopicNextAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SubscriptionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="575f2-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="575f2-130">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="575f2-131">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="575f2-131">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="575f2-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="575f2-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="575f2-133">指定したトピックの下のすべてのサブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="575f2-133">List all the subscriptions under a specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>