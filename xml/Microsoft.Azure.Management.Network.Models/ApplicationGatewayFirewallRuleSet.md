<Type Name="ApplicationGatewayFirewallRuleSet" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayFirewallRuleSet : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayFirewallRuleSet extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayFirewallRuleSet&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayFirewallRuleSet = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f05c2-101">Web アプリケーション ファイアウォール ルールを設定します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-101">A web application firewall rule set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFirewallRuleSet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.#ctor" />
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
            <span data-ttu-id="f05c2-102">ApplicationGatewayFirewallRuleSet クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-102">Initializes a new instance of the ApplicationGatewayFirewallRuleSet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayFirewallRuleSet (string ruleSetType, string ruleSetVersion, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup&gt; ruleGroups, string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string ruleSetType, string ruleSetVersion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup&gt; ruleGroups, string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup},System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ruleSetType As String, ruleSetVersion As String, ruleGroups As IList(Of ApplicationGatewayFirewallRuleGroup), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup&gt; * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet (ruleSetType, ruleSetVersion, ruleGroups, id, name, type, location, tags, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ruleSetType" Type="System.String" />
        <Parameter Name="ruleSetVersion" Type="System.String" />
        <Parameter Name="ruleGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleSetType"><span data-ttu-id="f05c2-103">Web アプリケーション ファイアウォール規則の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-103">The type of the web application firewall rule set.</span></span></param>
        <param name="ruleSetVersion"><span data-ttu-id="f05c2-104">Web アプリケーション ファイアウォール ルールのバージョンでは、種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-104">The version of the web application firewall rule set type.</span></span></param>
        <param name="ruleGroups"><span data-ttu-id="f05c2-105">Web アプリケーション ファイアウォール ルールのルール グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-105">The rule groups of the web application firewall rule set.</span></span></param>
        <param name="id"><span data-ttu-id="f05c2-106">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="f05c2-106">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="f05c2-107">リソース名。</span><span class="sxs-lookup"><span data-stu-id="f05c2-107">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="f05c2-108">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="f05c2-108">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="f05c2-109">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="f05c2-109">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="f05c2-110">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="f05c2-110">Resource tags.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="f05c2-111">Web アプリケーション ファイアウォール規則のプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-111">The provisioning state of the web application firewall rule set.</span></span></param>
        <summary>
            <span data-ttu-id="f05c2-112">ApplicationGatewayFirewallRuleSet クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-112">Initializes a new instance of the ApplicationGatewayFirewallRuleSet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f05c2-113">取得または web アプリケーション ファイアウォール ルールのセットのプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-113">Gets or sets the provisioning state of the web application firewall rule set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup&gt; RuleGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup&gt; RuleGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.RuleGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleGroups As IList(Of ApplicationGatewayFirewallRuleGroup)" />
      <MemberSignature Language="F#" Value="member this.RuleGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.RuleGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ruleGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f05c2-114">取得または web アプリケーション ファイアウォール ルールのセットのルール グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-114">Gets or sets the rule groups of the web application firewall rule set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleSetType">
      <MemberSignature Language="C#" Value="public string RuleSetType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleSetType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.RuleSetType" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleSetType As String" />
      <MemberSignature Language="F#" Value="member this.RuleSetType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.RuleSetType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ruleSetType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f05c2-115">取得または web アプリケーション ファイアウォール ルールのセットの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-115">Gets or sets the type of the web application firewall rule set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleSetVersion">
      <MemberSignature Language="C#" Value="public string RuleSetVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleSetVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.RuleSetVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleSetVersion As String" />
      <MemberSignature Language="F#" Value="member this.RuleSetVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.RuleSetVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ruleSetVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f05c2-116">取得または web アプリケーション ファイアウォール ルール セットの種類のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-116">Gets or sets the version of the web application firewall rule set type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayFirewallRuleSet.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayFirewallRuleSet.Validate " />
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
            <span data-ttu-id="f05c2-117">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f05c2-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f05c2-118">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f05c2-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>