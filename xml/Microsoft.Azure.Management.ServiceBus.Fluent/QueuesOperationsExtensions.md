<Type Name="QueuesOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class QueuesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueuesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module QueuesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type QueuesOperationsExtensions = class" />
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
            <span data-ttu-id="e9f6e-101">QueuesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-101">Extension methods for QueuesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * string * string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, queueName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e9f6e-103">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e9f6e-104">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="e9f6e-104">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="e9f6e-105">キュー名。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-105">The queue name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e9f6e-106">作成またはキュー リソースの更新に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-106">Parameters supplied to create or update a queue resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-108">作成するか、Service Bus キューを更新します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-108">Creates or updates a Service Bus queue.</span></span> <span data-ttu-id="e9f6e-109">この操作は、べき等です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-109">This operation is idempotent.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639395.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt; rights, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt; rights, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * string * string * string * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, rights, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e9f6e-111">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-111">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e9f6e-112">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="e9f6e-112">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="e9f6e-113">キュー名。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-113">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="e9f6e-114">Authorizationrule 名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-114">The authorizationrule name.</span></span>
            </param>
        <param name="rights">
            <span data-ttu-id="e9f6e-115">ルールに関連付けられている権限。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-115">The rights associated with the rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-117">キューの承認規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-117">Creates an authorization rule for a queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, queueName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e9f6e-119">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-119">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e9f6e-120">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="e9f6e-120">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="e9f6e-121">キュー名。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-121">The queue name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-123">リソース グループ内の指定した名前空間、キューを削除します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-123">Deletes a queue from the specified namespace in a resource group.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639411.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e9f6e-125">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-125">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e9f6e-126">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="e9f6e-126">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="e9f6e-127">キュー名。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-127">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="e9f6e-128">Authorizationrule 名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-128">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-130">キューの承認規則を削除します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-130">Deletes a queue authorization rule.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705609.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, queueName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e9f6e-132">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-132">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e9f6e-133">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="e9f6e-133">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="e9f6e-134">キュー名。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-134">The queue name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-136">指定したキューの説明を返します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-136">Returns a description for the specified queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639380.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e9f6e-138">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-138">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e9f6e-139">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="e9f6e-139">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="e9f6e-140">キュー名。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-140">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="e9f6e-141">Authorizationrule 名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-141">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-143">ルールの名前で、キューの承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-143">Gets an authorization rule for a queue by rule name.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705611.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, queueName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e9f6e-145">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-145">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e9f6e-146">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="e9f6e-146">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="e9f6e-147">キュー名。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-147">The queue name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-149">キューのすべての承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-149">Gets all authorization rules for a queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705607.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-150">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e9f6e-151">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-151">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-153">キューのすべての承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-153">Gets all authorization rules for a queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705607.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;&gt; ListByNamespaceAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;&gt; ListByNamespaceAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.ListByNamespaceAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.ListByNamespaceAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;ListByNamespaceAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e9f6e-155">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-155">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e9f6e-156">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="e9f6e-156">The namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-158">名前空間内のキューを取得します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-158">Gets the queues within a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639415.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;&gt; ListByNamespaceNextAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;&gt; ListByNamespaceNextAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.ListByNamespaceNextAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceNextAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.ListByNamespaceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;ListByNamespaceNextAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.QueueInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-159">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e9f6e-160">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-160">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-162">名前空間内のキューを取得します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-162">Gets the queues within a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639415.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; ListKeysAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; ListKeysAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;ListKeysAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e9f6e-164">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-164">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e9f6e-165">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="e9f6e-165">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="e9f6e-166">キュー名。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-166">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="e9f6e-167">Authorizationrule 名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-167">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-169">キューにプライマリとセカンダリの接続文字列です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-169">Primary and secondary connection strings to the queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705608.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; policykey = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; policykey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, policykey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.Fluent.QueuesOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.Fluent.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="policykey" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e9f6e-170">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e9f6e-171">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-171">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="e9f6e-172">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="e9f6e-172">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="e9f6e-173">キュー名。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-173">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="e9f6e-174">Authorizationrule 名前です。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-174">The authorizationrule name.</span></span>
            </param>
        <param name="policykey">
            <span data-ttu-id="e9f6e-175">再生成する必要があるキー。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-175">Key that needs to be regenerated.</span></span> <span data-ttu-id="e9f6e-176">使用可能な値が含まれます: 'PrimaryKey'、'SecondaryKey'</span><span class="sxs-lookup"><span data-stu-id="e9f6e-176">Possible values include: 'PrimaryKey', 'SecondaryKey'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e9f6e-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e9f6e-178">キューへのプライマリまたはセカンダリの接続文字列を再生成します。</span><span class="sxs-lookup"><span data-stu-id="e9f6e-178">Regenerates the primary or secondary connection strings to the queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705606.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>