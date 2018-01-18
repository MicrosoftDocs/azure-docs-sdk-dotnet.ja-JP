<Type Name="SubscriptionPolicies" FullName="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies">
  <TypeSignature Language="C#" Value="public class SubscriptionPolicies" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionPolicies extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionPolicies" />
  <TypeSignature Language="F#" Value="type SubscriptionPolicies = class" />
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
            <span data-ttu-id="3ff4e-101">サブスクリプション ポリシー。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-101">Subscription policies.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionPolicies ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3ff4e-102">SubscriptionPolicies クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-102">Initializes a new instance of the SubscriptionPolicies class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionPolicies (string locationPlacementId = null, string quotaId = null, Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt; spendingLimit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string locationPlacementId, string quotaId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt; spendingLimit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional locationPlacementId As String = null, Optional quotaId As String = null, Optional spendingLimit As Nullable(Of SpendingLimit) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies : string * string * Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies" Usage="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies (locationPlacementId, quotaId, spendingLimit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="locationPlacementId" Type="System.String" />
        <Parameter Name="quotaId" Type="System.String" />
        <Parameter Name="spendingLimit" Type="System.Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt;" />
      </Parameters>
      <Docs>
        <param name="locationPlacementId"><span data-ttu-id="3ff4e-103">場所の配置のサブスクリプション id です。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-103">The subscription location placement ID.</span></span> <span data-ttu-id="3ff4e-104">ID は、どの地域は、サブスクリプションの表示を示します。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-104">The ID indicates which regions are visible for a subscription.</span></span> <span data-ttu-id="3ff4e-105">たとえば、場所配置 Id の Public_2014-09-01 を使用してサブスクリプションは、パブリックの Azure のリージョンにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-105">For example, a subscription with a location placement Id of Public_2014-09-01 has access to Azure public regions.</span></span></param>
        <param name="quotaId"><span data-ttu-id="3ff4e-106">サブスクリプションのクォータの id。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-106">The subscription quota ID.</span></span></param>
        <param name="spendingLimit"><span data-ttu-id="3ff4e-107">サブスクリプションの使用制限します。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-107">The subscription spending limit.</span></span>
            <span data-ttu-id="3ff4e-108">使用可能な値が含まれます 'On'、'Off'、'CurrentPeriodOff'。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-108">Possible values include: 'On', 'Off', 'CurrentPeriodOff'</span></span></param>
        <summary>
            <span data-ttu-id="3ff4e-109">SubscriptionPolicies クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-109">Initializes a new instance of the SubscriptionPolicies class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationPlacementId">
      <MemberSignature Language="C#" Value="public string LocationPlacementId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocationPlacementId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.LocationPlacementId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocationPlacementId As String" />
      <MemberSignature Language="F#" Value="member this.LocationPlacementId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.LocationPlacementId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locationPlacementId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ff4e-110">サブスクリプションの場所の配置 ID を取得します</span><span class="sxs-lookup"><span data-stu-id="3ff4e-110">Gets the subscription location placement ID.</span></span> <span data-ttu-id="3ff4e-111">ID は、どの地域は、サブスクリプションの表示を示します。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-111">The ID indicates which regions are visible for a subscription.</span></span> <span data-ttu-id="3ff4e-112">たとえば、場所配置 Id の Public_2014-09-01 を使用してサブスクリプションは、パブリックの Azure のリージョンにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-112">For example, a subscription with a location placement Id of Public_2014-09-01 has access to Azure public regions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotaId">
      <MemberSignature Language="C#" Value="public string QuotaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotaId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.QuotaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QuotaId As String" />
      <MemberSignature Language="F#" Value="member this.QuotaId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.QuotaId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quotaId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ff4e-113">サブスクリプションのクォータの ID を取得します</span><span class="sxs-lookup"><span data-stu-id="3ff4e-113">Gets the subscription quota ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SpendingLimit">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt; SpendingLimit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt; SpendingLimit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.SpendingLimit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SpendingLimit As Nullable(Of SpendingLimit)" />
      <MemberSignature Language="F#" Value="member this.SpendingLimit : Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.SpendingLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="spendingLimit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ff4e-114">サブスクリプションの使用制限を取得します。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-114">Gets the subscription spending limit.</span></span> <span data-ttu-id="3ff4e-115">使用可能な値が含まれます 'On'、'Off'、'CurrentPeriodOff'。</span><span class="sxs-lookup"><span data-stu-id="3ff4e-115">Possible values include: 'On', 'Off', 'CurrentPeriodOff'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>