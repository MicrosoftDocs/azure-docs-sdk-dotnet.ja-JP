<Type Name="NetworkRuleSet" FullName="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet">
  <TypeSignature Language="C#" Value="public class NetworkRuleSet" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkRuleSet extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkRuleSet" />
  <TypeSignature Language="F#" Value="type NetworkRuleSet = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f6066-101">ネットワーク ルール セット</span><span class="sxs-lookup"><span data-stu-id="f6066-101">Network rule set</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkRuleSet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f6066-102">NetworkRuleSet クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f6066-102">Initializes a new instance of the NetworkRuleSet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkRuleSet (Microsoft.Azure.Management.Storage.Models.DefaultAction defaultAction, string bypass = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; virtualNetworkRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt; ipRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Storage.Models.DefaultAction defaultAction, string bypass, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; virtualNetworkRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.IPRule&gt; ipRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.#ctor(Microsoft.Azure.Management.Storage.Models.DefaultAction,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule},System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.IPRule})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.NetworkRuleSet : Microsoft.Azure.Management.Storage.Models.DefaultAction * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt; -&gt; Microsoft.Azure.Management.Storage.Models.NetworkRuleSet" Usage="new Microsoft.Azure.Management.Storage.Models.NetworkRuleSet (defaultAction, bypass, virtualNetworkRules, ipRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="defaultAction" Type="Microsoft.Azure.Management.Storage.Models.DefaultAction" />
        <Parameter Name="bypass" Type="System.String" />
        <Parameter Name="virtualNetworkRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt;" />
        <Parameter Name="ipRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt;" />
      </Parameters>
      <Docs>
        <param name="defaultAction"><span data-ttu-id="f6066-103">既定のアクションの指定を許可またはその他の規則に一致しないときを拒否します。</span><span class="sxs-lookup"><span data-stu-id="f6066-103">Specifies the default action of allow or deny when no other rules match.</span></span> <span data-ttu-id="f6066-104">使用可能な値が含まれます 'の Allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="f6066-104">Possible values include: 'Allow', 'Deny'</span></span></param>
        <param name="bypass"><span data-ttu-id="f6066-105">ログ記録/メトリック/AzureServices に対してトラフィックがバイパスされるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="f6066-105">Specifies whether traffic is bypassed for Logging/Metrics/AzureServices.</span></span> <span data-ttu-id="f6066-106">有効値は、ログ記録の任意の組み合わせ |メトリック |AzureServices (たとえば、「ログ、メトリック」)、または None それら traffics の [なし] をバイパスします。</span><span class="sxs-lookup"><span data-stu-id="f6066-106">Possible values are any combination of Logging|Metrics|AzureServices (For example, "Logging, Metrics"), or None to bypass none of those traffics.</span></span> <span data-ttu-id="f6066-107">使用可能な値が含まれます 'None'、'Logging'、'メトリック'、'AzureServices'。</span><span class="sxs-lookup"><span data-stu-id="f6066-107">Possible values include: 'None', 'Logging', 'Metrics', 'AzureServices'</span></span></param>
        <param name="virtualNetworkRules"><span data-ttu-id="f6066-108">仮想ネットワーク ルールを設定します。</span><span class="sxs-lookup"><span data-stu-id="f6066-108">Sets the virtual network rules</span></span></param>
        <param name="ipRules"><span data-ttu-id="f6066-109">IP ACL ルールを設定します。</span><span class="sxs-lookup"><span data-stu-id="f6066-109">Sets the IP ACL rules</span></span></param>
        <summary>
            <span data-ttu-id="f6066-110">NetworkRuleSet クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f6066-110">Initializes a new instance of the NetworkRuleSet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Bypass">
      <MemberSignature Language="C#" Value="public string Bypass { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Bypass" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.Bypass" />
      <MemberSignature Language="VB.NET" Value="Public Property Bypass As String" />
      <MemberSignature Language="F#" Value="member this.Bypass : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.Bypass" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bypass")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6066-111">取得または設定は、ログ記録/メトリック/AzureServices に対してトラフィックがバイパスされるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="f6066-111">Gets or sets specifies whether traffic is bypassed for Logging/Metrics/AzureServices.</span></span> <span data-ttu-id="f6066-112">有効値は、ログ記録の任意の組み合わせ |メトリック |AzureServices (たとえば、「ログ、メトリック」)、または None それら traffics の [なし] をバイパスします。</span><span class="sxs-lookup"><span data-stu-id="f6066-112">Possible values are any combination of Logging|Metrics|AzureServices (For example, "Logging, Metrics"), or None to bypass none of those traffics.</span></span> <span data-ttu-id="f6066-113">使用可能な値が含まれます 'None'、'Logging'、'メトリック'、'AzureServices'。</span><span class="sxs-lookup"><span data-stu-id="f6066-113">Possible values include: 'None', 'Logging', 'Metrics', 'AzureServices'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultAction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.DefaultAction DefaultAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Models.DefaultAction DefaultAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.DefaultAction" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultAction As DefaultAction" />
      <MemberSignature Language="F#" Value="member this.DefaultAction : Microsoft.Azure.Management.Storage.Models.DefaultAction with get, set" Usage="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.DefaultAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.DefaultAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6066-114">取得または設定の既定のアクションを指定を許可またはその他の規則に一致しないときを拒否します。</span><span class="sxs-lookup"><span data-stu-id="f6066-114">Gets or sets specifies the default action of allow or deny when no other rules match.</span></span> <span data-ttu-id="f6066-115">使用可能な値が含まれます 'の Allow'、'拒否'。</span><span class="sxs-lookup"><span data-stu-id="f6066-115">Possible values include: 'Allow', 'Deny'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt; IpRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.IPRule&gt; IpRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.IpRules" />
      <MemberSignature Language="VB.NET" Value="Public Property IpRules As IList(Of IPRule)" />
      <MemberSignature Language="F#" Value="member this.IpRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.IpRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.IPRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6066-116">取得または設定 IP ACL の規則を設定します。</span><span class="sxs-lookup"><span data-stu-id="f6066-116">Gets or sets sets the IP ACL rules</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkRuleSet.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f6066-117">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f6066-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f6066-118">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f6066-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; VirtualNetworkRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; VirtualNetworkRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.VirtualNetworkRules" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkRules As IList(Of VirtualNetworkRule)" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet.VirtualNetworkRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualNetworkRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.VirtualNetworkRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6066-119">取得または設定は、仮想ネットワーク ルールを設定します。</span><span class="sxs-lookup"><span data-stu-id="f6066-119">Gets or sets sets the virtual network rules</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>