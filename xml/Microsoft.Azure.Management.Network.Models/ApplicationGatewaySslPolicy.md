<Type Name="ApplicationGatewaySslPolicy" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy">
  <TypeSignature Language="C#" Value="public class ApplicationGatewaySslPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewaySslPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewaySslPolicy" />
  <TypeSignature Language="F#" Value="type ApplicationGatewaySslPolicy = class" />
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
            <span data-ttu-id="5f07b-101">アプリケーション ゲートウェイ Ssl ポリシー。</span><span class="sxs-lookup"><span data-stu-id="5f07b-101">Application Gateway Ssl policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewaySslPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.#ctor" />
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
            <span data-ttu-id="5f07b-102">ApplicationGatewaySslPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5f07b-102">Initializes a new instance of the ApplicationGatewaySslPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewaySslPolicy (System.Collections.Generic.IList&lt;string&gt; disabledSslProtocols = null, string policyType = null, string policyName = null, System.Collections.Generic.IList&lt;string&gt; cipherSuites = null, string minProtocolVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; disabledSslProtocols, string policyType, string policyName, class System.Collections.Generic.IList`1&lt;string&gt; cipherSuites, string minProtocolVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.#ctor(System.Collections.Generic.IList{System.String},System.String,System.String,System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional disabledSslProtocols As IList(Of String) = null, Optional policyType As String = null, Optional policyName As String = null, Optional cipherSuites As IList(Of String) = null, Optional minProtocolVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy : System.Collections.Generic.IList&lt;string&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy (disabledSslProtocols, policyType, policyName, cipherSuites, minProtocolVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="disabledSslProtocols" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="policyType" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cipherSuites" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="minProtocolVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="disabledSslProtocols"><span data-ttu-id="5f07b-103">Ssl プロトコルを使用して、アプリケーション ゲートウェイでは無効にします。</span><span class="sxs-lookup"><span data-stu-id="5f07b-103">Ssl protocols to be disabled on application gateway.</span></span></param>
        <param name="policyType"><span data-ttu-id="5f07b-104">Ssl ポリシーの種類。</span><span class="sxs-lookup"><span data-stu-id="5f07b-104">Type of Ssl Policy.</span></span> <span data-ttu-id="5f07b-105">使用可能な値が含まれます: '定義済み'、'Custom'</span><span class="sxs-lookup"><span data-stu-id="5f07b-105">Possible values include: 'Predefined', 'Custom'</span></span></param>
        <param name="policyName"><span data-ttu-id="5f07b-106">Ssl の名前には、ポリシーが定義されています。</span><span class="sxs-lookup"><span data-stu-id="5f07b-106">Name of Ssl predefined policy.</span></span> <span data-ttu-id="5f07b-107">使用可能な値が含まれます: 'AppGwSslPolicy20150501'、'AppGwSslPolicy20170401'、'AppGwSslPolicy20170401S'</span><span class="sxs-lookup"><span data-stu-id="5f07b-107">Possible values include: 'AppGwSslPolicy20150501', 'AppGwSslPolicy20170401', 'AppGwSslPolicy20170401S'</span></span></param>
        <param name="cipherSuites"><span data-ttu-id="5f07b-108">アプリケーション ゲートウェイを指定した順序で有効にする Ssl 暗号スイート。</span><span class="sxs-lookup"><span data-stu-id="5f07b-108">Ssl cipher suites to be enabled in the specified order to application gateway.</span></span></param>
        <param name="minProtocolVersion"><span data-ttu-id="5f07b-109">アプリケーション ゲートウェイでサポートされるために Ssl プロトコルの最小バージョン。</span><span class="sxs-lookup"><span data-stu-id="5f07b-109">Minimum version of Ssl protocol to be supported on application gateway.</span></span> <span data-ttu-id="5f07b-110">使用可能な値が含まれます: 'TLSv1_0'、'TLSv1_1'、'TLSv1_2'</span><span class="sxs-lookup"><span data-stu-id="5f07b-110">Possible values include: 'TLSv1_0', 'TLSv1_1', 'TLSv1_2'</span></span></param>
        <summary>
            <span data-ttu-id="5f07b-111">ApplicationGatewaySslPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5f07b-111">Initializes a new instance of the ApplicationGatewaySslPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CipherSuites">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CipherSuites { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CipherSuites" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.CipherSuites" />
      <MemberSignature Language="VB.NET" Value="Public Property CipherSuites As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CipherSuites : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.CipherSuites" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cipherSuites")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f07b-112">取得またはアプリケーション ゲートウェイを指定した順序で有効にする ssl 暗号スイートを設定します。</span><span class="sxs-lookup"><span data-stu-id="5f07b-112">Gets or sets ssl cipher suites to be enabled in the specified order to application gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisabledSslProtocols">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DisabledSslProtocols { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DisabledSslProtocols" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.DisabledSslProtocols" />
      <MemberSignature Language="VB.NET" Value="Public Property DisabledSslProtocols As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DisabledSslProtocols : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.DisabledSslProtocols" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disabledSslProtocols")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f07b-113">取得または設定 ssl プロトコルを使用してアプリケーション ゲートウェイでは無効にします。</span><span class="sxs-lookup"><span data-stu-id="5f07b-113">Gets or sets ssl protocols to be disabled on application gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinProtocolVersion">
      <MemberSignature Language="C#" Value="public string MinProtocolVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MinProtocolVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.MinProtocolVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property MinProtocolVersion As String" />
      <MemberSignature Language="F#" Value="member this.MinProtocolVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.MinProtocolVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minProtocolVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f07b-114">取得またはアプリケーション ゲートウェイでサポートされるために Ssl プロトコルの最小バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="5f07b-114">Gets or sets minimum version of Ssl protocol to be supported on application gateway.</span></span> <span data-ttu-id="5f07b-115">使用可能な値が含まれます: 'TLSv1_0'、'TLSv1_1'、'TLSv1_2'</span><span class="sxs-lookup"><span data-stu-id="5f07b-115">Possible values include: 'TLSv1_0', 'TLSv1_1', 'TLSv1_2'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyName">
      <MemberSignature Language="C#" Value="public string PolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.PolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyName As String" />
      <MemberSignature Language="F#" Value="member this.PolicyName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.PolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f07b-116">取得または定義済みの Ssl ポリシーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="5f07b-116">Gets or sets name of Ssl predefined policy.</span></span> <span data-ttu-id="5f07b-117">使用可能な値が含まれます: 'AppGwSslPolicy20150501'、'AppGwSslPolicy20170401'、'AppGwSslPolicy20170401S'</span><span class="sxs-lookup"><span data-stu-id="5f07b-117">Possible values include: 'AppGwSslPolicy20150501', 'AppGwSslPolicy20170401', 'AppGwSslPolicy20170401S'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyType">
      <MemberSignature Language="C#" Value="public string PolicyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.PolicyType" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyType As String" />
      <MemberSignature Language="F#" Value="member this.PolicyType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewaySslPolicy.PolicyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f07b-118">取得または Ssl ポリシーの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="5f07b-118">Gets or sets type of Ssl Policy.</span></span> <span data-ttu-id="5f07b-119">使用可能な値が含まれます: '定義済み'、'Custom'</span><span class="sxs-lookup"><span data-stu-id="5f07b-119">Possible values include: 'Predefined', 'Custom'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>