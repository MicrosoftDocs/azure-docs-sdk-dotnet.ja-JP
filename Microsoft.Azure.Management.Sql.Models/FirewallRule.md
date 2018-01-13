<Type Name="FirewallRule" FullName="Microsoft.Azure.Management.Sql.Models.FirewallRule">
  <TypeSignature Language="C#" Value="public class FirewallRule : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FirewallRule extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.FirewallRule" />
  <TypeSignature Language="VB.NET" Value="Public Class FirewallRule&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type FirewallRule = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.SubResource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e5bb5-101">サーバーのファイアウォール ルールを表します。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-101">Represents a server firewall rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FirewallRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FirewallRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e5bb5-102">FirewallRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-102">Initializes a new instance of the FirewallRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FirewallRule (string startIpAddress, string endIpAddress, string id = null, string name = null, string type = null, string kind = null, string location = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string startIpAddress, string endIpAddress, string id, string name, string type, string kind, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FirewallRule.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startIpAddress As String, endIpAddress As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As String = null, Optional location As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.FirewallRule : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.FirewallRule" Usage="new Microsoft.Azure.Management.Sql.Models.FirewallRule (startIpAddress, endIpAddress, id, name, type, kind, location)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startIpAddress" Type="System.String" />
        <Parameter Name="endIpAddress" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIpAddress"><span data-ttu-id="e5bb5-103">ファイアウォール規則の開始 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-103">The start IP address of the firewall rule.</span></span> <span data-ttu-id="e5bb5-104">IPv4 形式にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-104">Must be IPv4 format.</span></span> <span data-ttu-id="e5bb5-105">表すすべての Azure 内部 IP アドレスを使用して値 '0.0.0.0' です。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-105">Use value '0.0.0.0' to represent all Azure-internal IP addresses.</span></span></param>
        <param name="endIpAddress"><span data-ttu-id="e5bb5-106">ファイアウォール規則の終了 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-106">The end IP address of the firewall rule.</span></span>
            <span data-ttu-id="e5bb5-107">IPv4 形式にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-107">Must be IPv4 format.</span></span> <span data-ttu-id="e5bb5-108">StartIpAddress 以上にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-108">Must be greater than or equal to startIpAddress.</span></span> <span data-ttu-id="e5bb5-109">表すすべての Azure 内部 IP アドレスを使用して値 '0.0.0.0' です。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-109">Use value '0.0.0.0' to represent all Azure-internal IP addresses.</span></span></param>
        <param name="id"><span data-ttu-id="e5bb5-110">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="e5bb5-110">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="e5bb5-111">リソース名。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-111">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="e5bb5-112">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-112">Resource type.</span></span></param>
        <param name="kind"><span data-ttu-id="e5bb5-113">このファイアウォール規則を含むサーバーの種類。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-113">Kind of server that contains this firewall rule.</span></span></param>
        <param name="location"><span data-ttu-id="e5bb5-114">このファイアウォール規則を含むサーバーの場所です。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-114">Location of the server that contains this firewall rule.</span></span></param>
        <summary>
            <span data-ttu-id="e5bb5-115">FirewallRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-115">Initializes a new instance of the FirewallRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndIpAddress">
      <MemberSignature Language="C#" Value="public string EndIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FirewallRule.EndIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FirewallRule.EndIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5bb5-116">取得またはファイアウォール規則の終了 IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-116">Gets or sets the end IP address of the firewall rule.</span></span> <span data-ttu-id="e5bb5-117">IPv4 形式にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-117">Must be IPv4 format.</span></span> <span data-ttu-id="e5bb5-118">StartIpAddress 以上にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-118">Must be greater than or equal to startIpAddress.</span></span> <span data-ttu-id="e5bb5-119">表すすべての Azure 内部 IP アドレスを使用して値 '0.0.0.0' です。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-119">Use value '0.0.0.0' to represent all Azure-internal IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FirewallRule.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.FirewallRule.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5bb5-120">このファイアウォール規則を含むサーバーの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-120">Gets kind of server that contains this firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FirewallRule.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.FirewallRule.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5bb5-121">このファイアウォール規則を含むサーバーの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-121">Gets location of the server that contains this firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIpAddress">
      <MemberSignature Language="C#" Value="public string StartIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.FirewallRule.StartIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.FirewallRule.StartIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e5bb5-122">取得またはファイアウォール規則の開始 IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-122">Gets or sets the start IP address of the firewall rule.</span></span> <span data-ttu-id="e5bb5-123">IPv4 形式にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-123">Must be IPv4 format.</span></span> <span data-ttu-id="e5bb5-124">表すすべての Azure 内部 IP アドレスを使用して値 '0.0.0.0' です。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-124">Use value '0.0.0.0' to represent all Azure-internal IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.FirewallRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="firewallRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e5bb5-125">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-125">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5bb5-126">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5bb5-126">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>