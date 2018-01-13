<Type Name="NotificationHubsOperationsExtensions" FullName="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NotificationHubsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NotificationHubsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NotificationHubsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NotificationHubsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="63077-101">NotificationHubsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="63077-101">Extension methods for NotificationHubsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult CheckAvailability (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult CheckAvailability(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CheckAvailability(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckAvailability (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, parameters As CheckAvailabilityParameters) As CheckAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckAvailability : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CheckAvailability (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-103">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-104">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-104">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63077-105">NotificationHub 名。</span><span class="sxs-lookup"><span data-stu-id="63077-105">The notificationHub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-106">名前空間に指定された notificationHub の可用性を確認します。</span><span class="sxs-lookup"><span data-stu-id="63077-106">Checks the availability of the given notificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CheckAvailabilityAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-108">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-109">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-109">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63077-110">NotificationHub 名。</span><span class="sxs-lookup"><span data-stu-id="63077-110">The notificationHub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-112">名前空間に指定された notificationHub の可用性を確認します。</span><span class="sxs-lookup"><span data-stu-id="63077-112">Checks the availability of the given notificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource CreateOrUpdate (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource CreateOrUpdate(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, parameters As NotificationHubCreateOrUpdateParameters) As NotificationHubResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, notificationHubName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-114">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-115">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-115">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-116">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-116">The notification hub name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63077-117">パラメーターは、作成/更新に NotificationHub リソースを指定します。</span><span class="sxs-lookup"><span data-stu-id="63077-117">Parameters supplied to the create/update a NotificationHub Resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-118">名前空間に NotificationHub の作成/更新します。</span><span class="sxs-lookup"><span data-stu-id="63077-118">Creates/Update a NotificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, notificationHubName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-120">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-121">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-121">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-122">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-122">The notification hub name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63077-123">パラメーターは、作成/更新に NotificationHub リソースを指定します。</span><span class="sxs-lookup"><span data-stu-id="63077-123">Parameters supplied to the create/update a NotificationHub Resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-125">名前空間に NotificationHub の作成/更新します。</span><span class="sxs-lookup"><span data-stu-id="63077-125">Creates/Update a NotificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource CreateOrUpdateAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource CreateOrUpdateAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAuthorizationRule (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, authorizationRuleName As String, parameters As SharedAccessAuthorizationRuleCreateOrUpdateParameters) As SharedAccessAuthorizationRuleResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAuthorizationRule (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-127">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-128">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-128">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-129">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-129">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="63077-130">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-130">Authorization Rule Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63077-131">共有アクセス認証ルール。</span><span class="sxs-lookup"><span data-stu-id="63077-131">The shared access authorization rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-132">A NotificationHub の承認規則の作成/更新</span><span class="sxs-lookup"><span data-stu-id="63077-132">Creates/Updates an authorization rule for a NotificationHub</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-134">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-135">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-135">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-136">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-136">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="63077-137">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-137">Authorization Rule Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63077-138">共有アクセス認証ルール。</span><span class="sxs-lookup"><span data-stu-id="63077-138">The shared access authorization rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-140">A NotificationHub の承認規則の作成/更新</span><span class="sxs-lookup"><span data-stu-id="63077-140">Creates/Updates an authorization rule for a NotificationHub</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.Delete(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, notificationHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-142">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-142">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-143">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-143">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-144">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-144">The notification hub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-145">名前空間に関連付けられた通知ハブを削除します。</span><span class="sxs-lookup"><span data-stu-id="63077-145">Deletes a notification hub associated with a namespace.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, notificationHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-147">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-147">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-148">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-148">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-149">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-149">The notification hub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-151">名前空間に関連付けられた通知ハブを削除します。</span><span class="sxs-lookup"><span data-stu-id="63077-151">Deletes a notification hub associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRule">
      <MemberSignature Language="C#" Value="public static void DeleteAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAuthorizationRule (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, authorizationRuleName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAuthorizationRule (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-153">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-153">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-154">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-154">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-155">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-155">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="63077-156">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-156">Authorization Rule Name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-157">NotificationHub の承認規則を削除します。</span><span class="sxs-lookup"><span data-stu-id="63077-157">Deletes a notificationHub authorization rule</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-159">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-160">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-160">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-161">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-161">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="63077-162">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-162">Authorization Rule Name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-164">NotificationHub の承認規則を削除します。</span><span class="sxs-lookup"><span data-stu-id="63077-164">Deletes a notificationHub authorization rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource Get (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource Get(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.Get(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String) As NotificationHubResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.Get (operations, resourceGroupName, namespaceName, notificationHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-166">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-166">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-167">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-167">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-168">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-168">The notification hub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-169">名前空間に関連付けられた通知ハブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="63077-169">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; GetAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; GetAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, notificationHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-170">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-171">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-171">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-172">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-172">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-173">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-173">The notification hub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-175">名前空間に関連付けられた通知ハブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="63077-175">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource GetAuthorizationRule (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource GetAuthorizationRule(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, authorizationRuleName As String) As SharedAccessAuthorizationRuleResource" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-177">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-177">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-178">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="63077-178">The namespace name</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-179">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-179">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="63077-180">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-180">authorization rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-181">名前では NotificationHub の承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="63077-181">Gets an authorization rule for a NotificationHub by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-183">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-183">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-184">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="63077-184">The namespace name</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-185">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-185">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="63077-186">承認規則の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-186">authorization rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-188">名前では NotificationHub の承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="63077-188">Gets an authorization rule for a NotificationHub by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPnsCredentials">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource GetPnsCredentials (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource GetPnsCredentials(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetPnsCredentials(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetPnsCredentials (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String) As PnsCredentialsResource" />
      <MemberSignature Language="F#" Value="static member GetPnsCredentials : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetPnsCredentials (operations, resourceGroupName, namespaceName, notificationHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-189">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-190">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-190">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-191">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-191">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-192">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-192">The notification hub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-193">通知ハブに関連付けられている PNS 資格情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="63077-193">Lists the PNS Credentials associated with a notification hub .</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPnsCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt; GetPnsCredentialsAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt; GetPnsCredentialsAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetPnsCredentialsAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPnsCredentialsAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.GetPnsCredentialsAsync (operations, resourceGroupName, namespaceName, notificationHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;GetPnsCredentialsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-195">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-195">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-196">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-196">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-197">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-197">The notification hub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-199">通知ハブに関連付けられている PNS 資格情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="63077-199">Lists the PNS Credentials associated with a notification hub .</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; List (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; List(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.List(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String) As IPage(Of NotificationHubResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.List (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-200">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-201">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-201">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-202">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-202">The namespace name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-203">名前空間に関連付けられた通知ハブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="63077-203">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;ListAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-205">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-205">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-206">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-206">The namespace name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-208">名前空間に関連付けられた通知ハブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="63077-208">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRules (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRules(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String) As IPage(Of SharedAccessAuthorizationRuleResource)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName, notificationHubName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-210">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-210">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-211">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="63077-211">The namespace name</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-212">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-212">The notification hub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-213">A NotificationHub の承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="63077-213">Gets the authorization rules for a NotificationHub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, notificationHubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-215">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-215">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-216">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="63077-216">The namespace name</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-217">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-217">The notification hub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-219">A NotificationHub の承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="63077-219">Gets the authorization rules for a NotificationHub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As INotificationHubsOperations, nextPageLink As String) As IPage(Of SharedAccessAuthorizationRuleResource)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-220">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-220">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="63077-221">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="63077-221">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-222">A NotificationHub の承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="63077-222">Gets the authorization rules for a NotificationHub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-223">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="63077-224">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="63077-224">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-226">A NotificationHub の承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="63077-226">Gets the authorization rules for a NotificationHub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys ListKeys (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys ListKeys(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListKeys(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, authorizationRuleName As String) As ResourceListKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-227">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-227">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-228">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-228">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-229">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-229">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-230">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-230">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="63077-231">指定した authorizationRule の NotificationHub の接続文字列。</span><span class="sxs-lookup"><span data-stu-id="63077-231">The connection string of the NotificationHub for the specified authorizationRule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-232">NotificationHub にプライマリとセカンダリの ConnectionStrings を取得します。</span><span class="sxs-lookup"><span data-stu-id="63077-232">Gets the Primary and Secondary ConnectionStrings to the NotificationHub</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;ListKeysAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-234">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-234">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-235">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-235">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-236">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-236">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="63077-237">指定した authorizationRule の NotificationHub の接続文字列。</span><span class="sxs-lookup"><span data-stu-id="63077-237">The connection string of the NotificationHub for the specified authorizationRule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-238">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-239">NotificationHub にプライマリとセカンダリの ConnectionStrings を取得します。</span><span class="sxs-lookup"><span data-stu-id="63077-239">Gets the Primary and Secondary ConnectionStrings to the NotificationHub</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; ListNext (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt; ListNext(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListNext(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As INotificationHubsOperations, nextPageLink As String) As IPage(Of NotificationHubResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-240">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="63077-241">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="63077-241">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-242">名前空間に関連付けられた通知ハブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="63077-242">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;ListNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.NotificationHubs.Models.NotificationHubResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-243">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="63077-244">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="63077-244">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-245">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-246">名前空間に関連付けられた通知ハブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="63077-246">Lists the notification hubs associated with a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys RegenerateKeys (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys RegenerateKeys(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.RegenerateKeys(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeys (operations As INotificationHubsOperations, resourceGroupName As String, namespaceName As String, notificationHubName As String, authorizationRuleName As String, parameters As PolicykeyResource) As ResourceListKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKeys : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource -&gt; Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.RegenerateKeys (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-247">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-248">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-248">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-249">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-249">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-250">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-250">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="63077-251">指定した authorizationRule の NotificationHub の接続文字列。</span><span class="sxs-lookup"><span data-stu-id="63077-251">The connection string of the NotificationHub for the specified authorizationRule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63077-252">NotificationHub 承認規則のキーを再生成する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="63077-252">Parameters supplied to regenerate the NotificationHub Authorization Rule Key.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-253">NotificationHub の承認規則にプライマリ/セカンダリ キーが再生成します。</span><span class="sxs-lookup"><span data-stu-id="63077-253">Regenerates the Primary/Secondary Keys to the NotificationHub Authorization Rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations operations, string resourceGroupName, string namespaceName, string notificationHubName, string authorizationRuleName, class Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations * string * string * string * string * Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, notificationHubName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NotificationHubsOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.ResourceListKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INotificationHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="notificationHubName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.PolicykeyResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="63077-254">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="63077-254">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="63077-255">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-255">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="63077-256">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="63077-256">The namespace name.</span></span>
            </param>
        <param name="notificationHubName">
            <span data-ttu-id="63077-257">通知ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="63077-257">The notification hub name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="63077-258">指定した authorizationRule の NotificationHub の接続文字列。</span><span class="sxs-lookup"><span data-stu-id="63077-258">The connection string of the NotificationHub for the specified authorizationRule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="63077-259">NotificationHub 承認規則のキーを再生成する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="63077-259">Parameters supplied to regenerate the NotificationHub Authorization Rule Key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="63077-260">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="63077-260">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="63077-261">NotificationHub の承認規則にプライマリ/セカンダリ キーが再生成します。</span><span class="sxs-lookup"><span data-stu-id="63077-261">Regenerates the Primary/Secondary Keys to the NotificationHub Authorization Rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>