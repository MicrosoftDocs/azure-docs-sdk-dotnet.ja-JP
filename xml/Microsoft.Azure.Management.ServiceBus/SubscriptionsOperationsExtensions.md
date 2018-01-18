<Type Name="SubscriptionsOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SubscriptionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SubscriptionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SubscriptionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SubscriptionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4f55e-101">SubscriptionsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4f55e-101">Extension methods for SubscriptionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBSubscription CreateOrUpdate (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, Microsoft.Azure.Management.ServiceBus.Models.SBSubscription parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription CreateOrUpdate(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBSubscription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISubscriptionsOperations, resourceGroupName As String, namespaceName As String, topicName As String, subscriptionName As String, parameters As SBSubscription) As SBSubscription" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBSubscription -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBSubscription" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, topicName, subscriptionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f55e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f55e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f55e-103">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4f55e-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="4f55e-104">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="4f55e-104">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="4f55e-105">トピック名。</span><span class="sxs-lookup"><span data-stu-id="4f55e-105">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="4f55e-106">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="4f55e-106">The subscription name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4f55e-107">サブスクリプション リソースを作成する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="4f55e-107">Parameters supplied to create a subscription resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f55e-108">トピック サブスクリプションを作成します。</span><span class="sxs-lookup"><span data-stu-id="4f55e-108">Creates a topic subscription.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639385.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, Microsoft.Azure.Management.ServiceBus.Models.SBSubscription parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBSubscription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBSubscription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBSubscription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f55e-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f55e-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f55e-110">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4f55e-110">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="4f55e-111">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="4f55e-111">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="4f55e-112">トピック名。</span><span class="sxs-lookup"><span data-stu-id="4f55e-112">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="4f55e-113">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="4f55e-113">The subscription name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4f55e-114">サブスクリプション リソースを作成する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="4f55e-114">Parameters supplied to create a subscription resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f55e-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f55e-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f55e-116">トピック サブスクリプションを作成します。</span><span class="sxs-lookup"><span data-stu-id="4f55e-116">Creates a topic subscription.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639385.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.Delete(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISubscriptionsOperations, resourceGroupName As String, namespaceName As String, topicName As String, subscriptionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, topicName, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f55e-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f55e-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f55e-118">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4f55e-118">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="4f55e-119">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="4f55e-119">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="4f55e-120">トピック名。</span><span class="sxs-lookup"><span data-stu-id="4f55e-120">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="4f55e-121">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="4f55e-121">The subscription name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f55e-122">指定したトピックからサブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="4f55e-122">Deletes a subscription from the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639381.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f55e-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f55e-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f55e-124">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4f55e-124">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="4f55e-125">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="4f55e-125">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="4f55e-126">トピック名。</span><span class="sxs-lookup"><span data-stu-id="4f55e-126">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="4f55e-127">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="4f55e-127">The subscription name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f55e-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f55e-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f55e-129">指定したトピックからサブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="4f55e-129">Deletes a subscription from the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639381.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBSubscription Get (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription Get(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.Get(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISubscriptionsOperations, resourceGroupName As String, namespaceName As String, topicName As String, subscriptionName As String) As SBSubscription" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBSubscription" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.Get (operations, resourceGroupName, namespaceName, topicName, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f55e-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f55e-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f55e-131">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4f55e-131">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="4f55e-132">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="4f55e-132">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="4f55e-133">トピック名。</span><span class="sxs-lookup"><span data-stu-id="4f55e-133">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="4f55e-134">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="4f55e-134">The subscription name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f55e-135">指定したトピックのサブスクリプションの説明を返します。</span><span class="sxs-lookup"><span data-stu-id="4f55e-135">Returns a subscription description for the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639402.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f55e-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f55e-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f55e-137">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4f55e-137">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="4f55e-138">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="4f55e-138">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="4f55e-139">トピック名。</span><span class="sxs-lookup"><span data-stu-id="4f55e-139">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="4f55e-140">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="4f55e-140">The subscription name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f55e-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f55e-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f55e-142">指定したトピックのサブスクリプションの説明を返します。</span><span class="sxs-lookup"><span data-stu-id="4f55e-142">Returns a subscription description for the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639402.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopic">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; ListByTopic (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; ListByTopic(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopic(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByTopic (operations As ISubscriptionsOperations, resourceGroupName As String, namespaceName As String, topicName As String) As IPage(Of SBSubscription)" />
      <MemberSignature Language="F#" Value="static member ListByTopic : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopic (operations, resourceGroupName, namespaceName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f55e-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f55e-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f55e-144">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4f55e-144">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="4f55e-145">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="4f55e-145">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="4f55e-146">トピック名。</span><span class="sxs-lookup"><span data-stu-id="4f55e-146">The topic name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f55e-147">指定したトピックの下のすべてのサブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4f55e-147">List all the subscriptions under a specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopicAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt; ListByTopicAsync (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt; ListByTopicAsync(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string resourceGroupName, string namespaceName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicAsync(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTopicAsync : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicAsync (operations, resourceGroupName, namespaceName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions/&lt;ListByTopicAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f55e-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f55e-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f55e-149">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4f55e-149">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="4f55e-150">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="4f55e-150">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="4f55e-151">トピック名。</span><span class="sxs-lookup"><span data-stu-id="4f55e-151">The topic name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f55e-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f55e-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f55e-153">指定したトピックの下のすべてのサブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4f55e-153">List all the subscriptions under a specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopicNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; ListByTopicNext (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt; ListByTopicNext(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicNext(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByTopicNext (operations As ISubscriptionsOperations, nextPageLink As String) As IPage(Of SBSubscription)" />
      <MemberSignature Language="F#" Value="static member ListByTopicNext : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f55e-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f55e-154">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4f55e-155">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4f55e-155">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f55e-156">指定したトピックの下のすべてのサブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4f55e-156">List all the subscriptions under a specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTopicNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt; ListByTopicNextAsync (this Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt; ListByTopicNextAsync(class Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicNextAsync(Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTopicNextAsync : Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions.ListByTopicNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.SubscriptionsOperationsExtensions/&lt;ListByTopicNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ISubscriptionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f55e-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f55e-157">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4f55e-158">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4f55e-158">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f55e-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f55e-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f55e-160">指定したトピックの下のすべてのサブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4f55e-160">List all the subscriptions under a specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639400.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>