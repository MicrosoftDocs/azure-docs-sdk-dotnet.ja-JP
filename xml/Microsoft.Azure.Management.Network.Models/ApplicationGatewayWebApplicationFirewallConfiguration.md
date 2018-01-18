<Type Name="ApplicationGatewayWebApplicationFirewallConfiguration" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayWebApplicationFirewallConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayWebApplicationFirewallConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayWebApplicationFirewallConfiguration" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayWebApplicationFirewallConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="907c5-101">アプリケーション ゲートウェイの web アプリケーション ファイアウォール構成します。</span><span class="sxs-lookup"><span data-stu-id="907c5-101">Application gateway web application firewall configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayWebApplicationFirewallConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="907c5-102">ApplicationGatewayWebApplicationFirewallConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="907c5-102">Initializes a new instance of the ApplicationGatewayWebApplicationFirewallConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayWebApplicationFirewallConfiguration (bool enabled, string firewallMode, string ruleSetType, string ruleSetVersion, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; disabledRuleGroups = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enabled, string firewallMode, string ruleSetType, string ruleSetVersion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; disabledRuleGroups) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.#ctor(System.Boolean,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enabled As Boolean, firewallMode As String, ruleSetType As String, ruleSetVersion As String, Optional disabledRuleGroups As IList(Of ApplicationGatewayFirewallDisabledRuleGroup) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration : bool * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration (enabled, firewallMode, ruleSetType, ruleSetVersion, disabledRuleGroups)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="firewallMode" Type="System.String" />
        <Parameter Name="ruleSetType" Type="System.String" />
        <Parameter Name="ruleSetVersion" Type="System.String" />
        <Parameter Name="disabledRuleGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="907c5-103">Web アプリケーション ファイアウォールが有効かどうかされません。</span><span class="sxs-lookup"><span data-stu-id="907c5-103">Whether the web application firewall is enabled or not.</span></span></param>
        <param name="firewallMode"><span data-ttu-id="907c5-104">Web アプリケーション ファイアウォール モードです。</span><span class="sxs-lookup"><span data-stu-id="907c5-104">Web application firewall mode.</span></span> <span data-ttu-id="907c5-105">使用可能な値が含まれます: '検出'、'防止'</span><span class="sxs-lookup"><span data-stu-id="907c5-105">Possible values include: 'Detection', 'Prevention'</span></span></param>
        <param name="ruleSetType"><span data-ttu-id="907c5-106">Web アプリケーション ファイアウォール規則の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="907c5-106">The type of the web application firewall rule set.</span></span> <span data-ttu-id="907c5-107">使用可能な値が: 'OWASP' です。</span><span class="sxs-lookup"><span data-stu-id="907c5-107">Possible values are: 'OWASP'.</span></span></param>
        <param name="ruleSetVersion"><span data-ttu-id="907c5-108">ルールのバージョンでは、種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="907c5-108">The version of the rule set type.</span></span></param>
        <param name="disabledRuleGroups"><span data-ttu-id="907c5-109">無効になっているルール グループです。</span><span class="sxs-lookup"><span data-stu-id="907c5-109">The disabled rule groups.</span></span></param>
        <summary>
            <span data-ttu-id="907c5-110">ApplicationGatewayWebApplicationFirewallConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="907c5-110">Initializes a new instance of the ApplicationGatewayWebApplicationFirewallConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisabledRuleGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; DisabledRuleGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; DisabledRuleGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.DisabledRuleGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property DisabledRuleGroups As IList(Of ApplicationGatewayFirewallDisabledRuleGroup)" />
      <MemberSignature Language="F#" Value="member this.DisabledRuleGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.DisabledRuleGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disabledRuleGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallDisabledRuleGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="907c5-111">取得または無効になっているルール グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="907c5-111">Gets or sets the disabled rule groups.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="907c5-112">取得または web アプリケーション ファイアウォールが有効かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="907c5-112">Gets or sets whether the web application firewall is enabled or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallMode">
      <MemberSignature Language="C#" Value="public string FirewallMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FirewallMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.FirewallMode" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallMode As String" />
      <MemberSignature Language="F#" Value="member this.FirewallMode : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.FirewallMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="firewallMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="907c5-113">取得または web アプリケーション ファイアウォール モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="907c5-113">Gets or sets web application firewall mode.</span></span> <span data-ttu-id="907c5-114">使用可能な値が含まれます: '検出'、'防止'</span><span class="sxs-lookup"><span data-stu-id="907c5-114">Possible values include: 'Detection', 'Prevention'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleSetType">
      <MemberSignature Language="C#" Value="public string RuleSetType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleSetType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.RuleSetType" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleSetType As String" />
      <MemberSignature Language="F#" Value="member this.RuleSetType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.RuleSetType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleSetType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="907c5-115">取得または web アプリケーション ファイアウォール ルールのセットの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="907c5-115">Gets or sets the type of the web application firewall rule set.</span></span>
            <span data-ttu-id="907c5-116">使用可能な値が: 'OWASP' です。</span><span class="sxs-lookup"><span data-stu-id="907c5-116">Possible values are: 'OWASP'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleSetVersion">
      <MemberSignature Language="C#" Value="public string RuleSetVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleSetVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.RuleSetVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleSetVersion As String" />
      <MemberSignature Language="F#" Value="member this.RuleSetVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.RuleSetVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleSetVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="907c5-117">取得または規則セットの種類のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="907c5-117">Gets or sets the version of the rule set type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayWebApplicationFirewallConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayWebApplicationFirewallConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="907c5-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="907c5-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="907c5-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="907c5-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>