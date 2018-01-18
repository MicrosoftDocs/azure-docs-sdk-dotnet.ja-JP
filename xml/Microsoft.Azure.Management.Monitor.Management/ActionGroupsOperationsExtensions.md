<Type Name="ActionGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActionGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActionGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActionGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ActionGroupsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5ba0d-101">ActionGroupsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-101">Extension methods for ActionGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource CreateOrUpdate (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource actionGroup);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource CreateOrUpdate(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource actionGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IActionGroupsOperations, resourceGroupName As String, actionGroupName As String, actionGroup As ActionGroupResource) As ActionGroupResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * string * string * Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, actionGroupName, actionGroup)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
        <Parameter Name="actionGroup" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba0d-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-103">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="5ba0d-104">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-104">The name of the action group.</span></span>
            </param>
        <param name="actionGroup">
            <span data-ttu-id="5ba0d-105">作成または更新に使用するアクション グループ。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-105">The action group to create or use for the update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-106">新しいアクション グループを作成または既存のものを更新します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-106">Create a new action group or update an existing one.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource actionGroup, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource actionGroup, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.String,System.String,Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * string * string * Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, actionGroupName, actionGroup, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
        <Parameter Name="actionGroup" Type="Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba0d-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-108">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="5ba0d-109">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-109">The name of the action group.</span></span>
            </param>
        <param name="actionGroup">
            <span data-ttu-id="5ba0d-110">作成または更新に使用するアクション グループ。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-110">The action group to create or use for the update.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ba0d-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-112">新しいアクション グループを作成または既存のものを更新します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-112">Create a new action group or update an existing one.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IActionGroupsOperations, resourceGroupName As String, actionGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.Delete (operations, resourceGroupName, actionGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba0d-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-114">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="5ba0d-115">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-115">The name of the action group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-116">アクション グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-116">Delete an action group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, actionGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba0d-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-118">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="5ba0d-119">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-119">The name of the action group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ba0d-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-121">アクション グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-121">Delete an action group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiver">
      <MemberSignature Language="C#" Value="public static void EnableReceiver (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, string receiverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void EnableReceiver(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, string receiverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.EnableReceiver(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub EnableReceiver (operations As IActionGroupsOperations, resourceGroupName As String, actionGroupName As String, receiverName As String)" />
      <MemberSignature Language="F#" Value="static member EnableReceiver : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.EnableReceiver (operations, resourceGroupName, actionGroupName, receiverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
        <Parameter Name="receiverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba0d-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-123">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="5ba0d-124">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-124">The name of the action group.</span></span>
            </param>
        <param name="receiverName">
            <span data-ttu-id="5ba0d-125">サブスクライブする受信者の名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-125">The name of the receiver to resubscribe.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-126">アクション グループ内の受信機を有効にします。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-126">Enable a receiver in an action group.</span></span> <span data-ttu-id="5ba0d-127">[有効] に、無効から受信側の状態を変更します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-127">This changes the receiver's status from Disabled to Enabled.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task EnableReceiverAsync (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, string receiverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task EnableReceiverAsync(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, string receiverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.EnableReceiverAsync(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableReceiverAsync : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.EnableReceiverAsync (operations, resourceGroupName, actionGroupName, receiverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions/&lt;EnableReceiverAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
        <Parameter Name="receiverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba0d-129">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-129">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="5ba0d-130">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-130">The name of the action group.</span></span>
            </param>
        <param name="receiverName">
            <span data-ttu-id="5ba0d-131">サブスクライブする受信者の名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-131">The name of the receiver to resubscribe.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ba0d-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-133">アクション グループ内の受信機を有効にします。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-133">Enable a receiver in an action group.</span></span> <span data-ttu-id="5ba0d-134">[有効] に、無効から受信側の状態を変更します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-134">This changes the receiver's status from Disabled to Enabled.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource Get (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource Get(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.Get(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IActionGroupsOperations, resourceGroupName As String, actionGroupName As String) As ActionGroupResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.Get (operations, resourceGroupName, actionGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba0d-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-136">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="5ba0d-137">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-137">The name of the action group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-138">アクション グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-138">Get an action group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt; GetAsync (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt; GetAsync(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, string actionGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, actionGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="actionGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba0d-140">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-140">The name of the resource group.</span></span>
            </param>
        <param name="actionGroupName">
            <span data-ttu-id="5ba0d-141">アクション グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-141">The name of the action group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ba0d-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-143">アクション グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-143">Get an action group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt; ListByResourceGroup (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt; ListByResourceGroup(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IActionGroupsOperations, resourceGroupName As String) As IEnumerable(Of ActionGroupResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba0d-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-145">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-146">リソース グループ内のすべてのアクション グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-146">Get a list of all action groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-147">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba0d-148">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-148">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ba0d-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-150">リソース グループ内のすべてのアクション グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-150">Get a list of all action groups in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionId">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt; ListBySubscriptionId (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt; ListBySubscriptionId(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.ListBySubscriptionId(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscriptionId (operations As IActionGroupsOperations) As IEnumerable(Of ActionGroupResource)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionId : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations -&gt; seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.ListBySubscriptionId operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-151">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-152">サブスクリプションのすべてのアクション グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-152">Get a list of all action groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt; ListBySubscriptionIdAsync (this Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt; ListBySubscriptionIdAsync(class Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.ListBySubscriptionIdAsync(Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionIdAsync : Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions.ListBySubscriptionIdAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.ActionGroupsOperationsExtensions/&lt;ListBySubscriptionIdAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ActionGroupResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.IActionGroupsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba0d-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-153">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5ba0d-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba0d-155">サブスクリプションのすべてのアクション グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5ba0d-155">Get a list of all action groups in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>