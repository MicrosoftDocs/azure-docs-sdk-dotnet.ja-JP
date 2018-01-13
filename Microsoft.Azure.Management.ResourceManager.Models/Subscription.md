<Type Name="Subscription" FullName="Microsoft.Azure.Management.ResourceManager.Models.Subscription">
  <TypeSignature Language="C#" Value="public class Subscription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Subscription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.Subscription" />
  <TypeSignature Language="VB.NET" Value="Public Class Subscription" />
  <TypeSignature Language="F#" Value="type Subscription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b3d88-101">サブスクリプション情報です。</span><span class="sxs-lookup"><span data-stu-id="b3d88-101">Subscription information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Subscription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.Subscription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b3d88-102">配信登録のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3d88-102">Initializes a new instance of the Subscription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Subscription (string id = null, string subscriptionId = null, string displayName = null, Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionState&gt; state = null, Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies subscriptionPolicies = null, string authorizationSource = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string subscriptionId, string displayName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ResourceManager.Models.SubscriptionState&gt; state, class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies subscriptionPolicies, string authorizationSource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.Subscription.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.ResourceManager.Models.SubscriptionState},Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.Subscription : string * string * string * Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionState&gt; * Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.Subscription" Usage="new Microsoft.Azure.Management.ResourceManager.Models.Subscription (id, subscriptionId, displayName, state, subscriptionPolicies, authorizationSource)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionState&gt;" />
        <Parameter Name="subscriptionPolicies" Type="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies" />
        <Parameter Name="authorizationSource" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="b3d88-103">サブスクリプションの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="b3d88-103">The fully qualified ID for the subscription.</span></span> <span data-ttu-id="b3d88-104">たとえば、/subscriptions/00000000-0000-0000-0000-000000000000 です。</span><span class="sxs-lookup"><span data-stu-id="b3d88-104">For example, /subscriptions/00000000-0000-0000-0000-000000000000.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="b3d88-105">サブスクリプション id。</span><span class="sxs-lookup"><span data-stu-id="b3d88-105">The subscription ID.</span></span></param>
        <param name="displayName"><span data-ttu-id="b3d88-106">サブスクリプションの表示名。</span><span class="sxs-lookup"><span data-stu-id="b3d88-106">The subscription display name.</span></span></param>
        <param name="state"><span data-ttu-id="b3d88-107">サブスクリプションの状態。</span><span class="sxs-lookup"><span data-stu-id="b3d88-107">The subscription state.</span></span> <span data-ttu-id="b3d88-108">使用可能な値は有効、警告済み、PastDue、無効な場合、および削除します。</span><span class="sxs-lookup"><span data-stu-id="b3d88-108">Possible values are Enabled, Warned, PastDue, Disabled, and Deleted.</span></span> <span data-ttu-id="b3d88-109">使用可能な値が含まれます: 'Enabled'、'警告'、'PastDue'、'Disabled'、'削除済み'</span><span class="sxs-lookup"><span data-stu-id="b3d88-109">Possible values include: 'Enabled', 'Warned', 'PastDue', 'Disabled', 'Deleted'</span></span></param>
        <param name="subscriptionPolicies"><span data-ttu-id="b3d88-110">サブスクリプションに従うポリシー。</span><span class="sxs-lookup"><span data-stu-id="b3d88-110">The subscription policies.</span></span></param>
        <param name="authorizationSource"><span data-ttu-id="b3d88-111">要求の承認のソース。</span><span class="sxs-lookup"><span data-stu-id="b3d88-111">The authorization source of the request.</span></span> <span data-ttu-id="b3d88-112">有効な値は、レガシ、RoleBased、Bypassed、ダイレクト管理の 1 つまたは複数の組み合わせです。</span><span class="sxs-lookup"><span data-stu-id="b3d88-112">Valid values are one or more combinations of Legacy, RoleBased, Bypassed, Direct and Management.</span></span> <span data-ttu-id="b3d88-113">たとえば、'レガシ、RoleBased' です。</span><span class="sxs-lookup"><span data-stu-id="b3d88-113">For example, 'Legacy, RoleBased'.</span></span></param>
        <summary>
            <span data-ttu-id="b3d88-114">配信登録のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3d88-114">Initializes a new instance of the Subscription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationSource">
      <MemberSignature Language="C#" Value="public string AuthorizationSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Subscription.AuthorizationSource" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationSource As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationSource : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.Subscription.AuthorizationSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authorizationSource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3d88-115">取得または要求の承認のソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="b3d88-115">Gets or sets the authorization source of the request.</span></span> <span data-ttu-id="b3d88-116">有効な値は、レガシ、RoleBased、Bypassed、ダイレクト管理の 1 つまたは複数の組み合わせです。</span><span class="sxs-lookup"><span data-stu-id="b3d88-116">Valid values are one or more combinations of Legacy, RoleBased, Bypassed, Direct and Management.</span></span> <span data-ttu-id="b3d88-117">たとえば、'レガシ、RoleBased' です。</span><span class="sxs-lookup"><span data-stu-id="b3d88-117">For example, 'Legacy, RoleBased'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Subscription.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Subscription.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3d88-118">サブスクリプションの表示名を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3d88-118">Gets the subscription display name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Subscription.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Subscription.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3d88-119">サブスクリプションの完全修飾 ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3d88-119">Gets the fully qualified ID for the subscription.</span></span> <span data-ttu-id="b3d88-120">たとえば、/subscriptions/00000000-0000-0000-0000-000000000000 です。</span><span class="sxs-lookup"><span data-stu-id="b3d88-120">For example, /subscriptions/00000000-0000-0000-0000-000000000000.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ResourceManager.Models.SubscriptionState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Subscription.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of SubscriptionState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionState&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.Subscription.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SubscriptionState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3d88-121">サブスクリプションの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3d88-121">Gets the subscription state.</span></span> <span data-ttu-id="b3d88-122">使用可能な値は有効、警告済み、PastDue、無効な場合、および削除します。</span><span class="sxs-lookup"><span data-stu-id="b3d88-122">Possible values are Enabled, Warned, PastDue, Disabled, and Deleted.</span></span> <span data-ttu-id="b3d88-123">使用可能な値が含まれます: 'Enabled'、'警告'、'PastDue'、'Disabled'、'削除済み'</span><span class="sxs-lookup"><span data-stu-id="b3d88-123">Possible values include: 'Enabled', 'Warned', 'PastDue', 'Disabled', 'Deleted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Subscription.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Subscription.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3d88-124">サブスクリプション ID を取得します</span><span class="sxs-lookup"><span data-stu-id="b3d88-124">Gets the subscription ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies SubscriptionPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies SubscriptionPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Subscription.SubscriptionPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionPolicies As SubscriptionPolicies" />
      <MemberSignature Language="F#" Value="member this.SubscriptionPolicies : Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.Subscription.SubscriptionPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionPolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3d88-125">取得またはサブスクリプション ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="b3d88-125">Gets or sets the subscription policies.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>