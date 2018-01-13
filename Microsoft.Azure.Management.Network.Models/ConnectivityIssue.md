<Type Name="ConnectivityIssue" FullName="Microsoft.Azure.Management.Network.Models.ConnectivityIssue">
  <TypeSignature Language="C#" Value="public class ConnectivityIssue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectivityIssue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ConnectivityIssue" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectivityIssue" />
  <TypeSignature Language="F#" Value="type ConnectivityIssue = class" />
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
            <span data-ttu-id="63230-101">接続を確認中に発生した問題に関する情報です。</span><span class="sxs-lookup"><span data-stu-id="63230-101">Information about an issue encountered in the process of checking for connectivity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityIssue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.#ctor" />
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
            <span data-ttu-id="63230-102">ConnectivityIssue クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="63230-102">Initializes a new instance of the ConnectivityIssue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityIssue (string origin = null, string severity = null, string type = null, System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string,string&gt;&gt; context = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string origin, string severity, string type, class System.Collections.Generic.IList`1&lt;class System.Collections.Generic.IDictionary`2&lt;string, string&gt;&gt; context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.Collections.Generic.IDictionary{System.String,System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional origin As String = null, Optional severity As String = null, Optional type As String = null, Optional context As IList(Of IDictionary(Of String, String)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ConnectivityIssue : string * string * string * System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string, string&gt;&gt; -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityIssue" Usage="new Microsoft.Azure.Management.Network.Models.ConnectivityIssue (origin, severity, type, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="severity" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="context" Type="System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="origin"><span data-ttu-id="63230-103">問題の原因です。</span><span class="sxs-lookup"><span data-stu-id="63230-103">The origin of the issue.</span></span> <span data-ttu-id="63230-104">使用可能な値が含まれます 'Local'、'受信'、'送信'。</span><span class="sxs-lookup"><span data-stu-id="63230-104">Possible values include: 'Local', 'Inbound', 'Outbound'</span></span></param>
        <param name="severity"><span data-ttu-id="63230-105">問題の重大度。</span><span class="sxs-lookup"><span data-stu-id="63230-105">The severity of the issue.</span></span> <span data-ttu-id="63230-106">使用可能な値が含まれます: 'Error'、'警告'</span><span class="sxs-lookup"><span data-stu-id="63230-106">Possible values include: 'Error', 'Warning'</span></span></param>
        <param name="type"><span data-ttu-id="63230-107">問題の種類。</span><span class="sxs-lookup"><span data-stu-id="63230-107">The type of issue.</span></span> <span data-ttu-id="63230-108">使用可能な値が含まれます: 'Unknown'、'AgentStopped'、'GuestFirewall'、'DnsResolution'、'SocketBind'、'NetworkSecurityRule'、'UserDefinedRoute'、'PortThrottled'、'Platform'</span><span class="sxs-lookup"><span data-stu-id="63230-108">Possible values include: 'Unknown', 'AgentStopped', 'GuestFirewall', 'DnsResolution', 'SocketBind', 'NetworkSecurityRule', 'UserDefinedRoute', 'PortThrottled', 'Platform'</span></span></param>
        <param name="context"><span data-ttu-id="63230-109">問題に関する追加のコンテキストを提供します。</span><span class="sxs-lookup"><span data-stu-id="63230-109">Provides additional context on the issue.</span></span></param>
        <summary>
            <span data-ttu-id="63230-110">ConnectivityIssue クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="63230-110">Initializes a new instance of the ConnectivityIssue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string,string&gt;&gt; Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Collections.Generic.IDictionary`2&lt;string, string&gt;&gt; Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As IList(Of IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="member this.Context : System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string, string&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="context")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63230-111">取得は、問題に関する追加のコンテキストを提供します。</span><span class="sxs-lookup"><span data-stu-id="63230-111">Gets provides additional context on the issue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Origin" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63230-112">問題の発生元を取得します。</span><span class="sxs-lookup"><span data-stu-id="63230-112">Gets the origin of the issue.</span></span> <span data-ttu-id="63230-113">使用可能な値が含まれます 'Local'、'受信'、'送信'。</span><span class="sxs-lookup"><span data-stu-id="63230-113">Possible values include: 'Local', 'Inbound', 'Outbound'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public string Severity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Severity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Severity As String" />
      <MemberSignature Language="F#" Value="member this.Severity : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63230-114">問題の重大度を取得します。</span><span class="sxs-lookup"><span data-stu-id="63230-114">Gets the severity of the issue.</span></span> <span data-ttu-id="63230-115">使用可能な値が含まれます: 'Error'、'警告'</span><span class="sxs-lookup"><span data-stu-id="63230-115">Possible values include: 'Error', 'Warning'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="63230-116">問題の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="63230-116">Gets the type of issue.</span></span> <span data-ttu-id="63230-117">使用可能な値が含まれます: 'Unknown'、'AgentStopped'、'GuestFirewall'、'DnsResolution'、'SocketBind'、'NetworkSecurityRule'、'UserDefinedRoute'、'PortThrottled'、'Platform'</span><span class="sxs-lookup"><span data-stu-id="63230-117">Possible values include: 'Unknown', 'AgentStopped', 'GuestFirewall', 'DnsResolution', 'SocketBind', 'NetworkSecurityRule', 'UserDefinedRoute', 'PortThrottled', 'Platform'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>