<Type Name="HostNameSslState" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState">
  <TypeSignature Language="C#" Value="public class HostNameSslState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HostNameSslState extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState" />
  <TypeSignature Language="VB.NET" Value="Public Class HostNameSslState" />
  <TypeSignature Language="F#" Value="type HostNameSslState = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="13fff-101">SSL が有効なホスト名です。</span><span class="sxs-lookup"><span data-stu-id="13fff-101">SSL-enabled hostname.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostNameSslState ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="13fff-102">HostNameSslState クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13fff-102">Initializes a new instance of the HostNameSslState class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostNameSslState (string name = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SslState&gt; sslState = null, string virtualIP = null, string thumbprint = null, Nullable&lt;bool&gt; toUpdate = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostType&gt; hostType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SslState&gt; sslState, string virtualIP, string thumbprint, valuetype System.Nullable`1&lt;bool&gt; toUpdate, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.HostType&gt; hostType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.SslState},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.HostType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional sslState As Nullable(Of SslState) = null, Optional virtualIP As String = null, Optional thumbprint As String = null, Optional toUpdate As Nullable(Of Boolean) = null, Optional hostType As Nullable(Of HostType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState : string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SslState&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostType&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState (name, sslState, virtualIP, thumbprint, toUpdate, hostType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sslState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SslState&gt;" />
        <Parameter Name="virtualIP" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="toUpdate" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostType&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="13fff-103">ホスト名です。</span><span class="sxs-lookup"><span data-stu-id="13fff-103">Hostname.</span></span></param>
        <param name="sslState"><span data-ttu-id="13fff-104">SSL の型。</span><span class="sxs-lookup"><span data-stu-id="13fff-104">SSL type.</span></span> <span data-ttu-id="13fff-105">使用可能な値が含まれます: '無効'、'SniEnabled'、'IpBasedEnabled'</span><span class="sxs-lookup"><span data-stu-id="13fff-105">Possible values include: 'Disabled', 'SniEnabled', 'IpBasedEnabled'</span></span></param>
        <param name="virtualIP"><span data-ttu-id="13fff-106">IP ベースの SSL の場合は、ホスト名に割り当てられている仮想 IP アドレスは有効です。</span><span class="sxs-lookup"><span data-stu-id="13fff-106">Virtual IP address assigned to the hostname if IP based SSL is enabled.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="13fff-107">SSL 証明書の拇印。</span><span class="sxs-lookup"><span data-stu-id="13fff-107">SSL certificate thumbprint.</span></span></param>
        <param name="toUpdate"><span data-ttu-id="13fff-108">設定&lt;コード&gt;true&lt;/code&gt;を既存のホスト名を更新します。</span><span class="sxs-lookup"><span data-stu-id="13fff-108">Set to &lt;code&gt;true&lt;/code&gt; to update existing hostname.</span></span></param>
        <param name="hostType"><span data-ttu-id="13fff-109">ホスト名が standard またはリポジトリのホスト名であるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="13fff-109">Indicates whether the hostname is a standard or repository hostname.</span></span> <span data-ttu-id="13fff-110">使用可能な値が含まれます: 'Standard'、'リポジトリ'</span><span class="sxs-lookup"><span data-stu-id="13fff-110">Possible values include: 'Standard', 'Repository'</span></span></param>
        <summary>
            <span data-ttu-id="13fff-111">HostNameSslState クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13fff-111">Initializes a new instance of the HostNameSslState class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostType&gt; HostType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.HostType&gt; HostType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.HostType" />
      <MemberSignature Language="VB.NET" Value="Public Property HostType As Nullable(Of HostType)" />
      <MemberSignature Language="F#" Value="member this.HostType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.HostType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hostType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13fff-112">取得または設定は、ホスト名が standard またはリポジトリのホスト名であるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="13fff-112">Gets or sets indicates whether the hostname is a standard or repository hostname.</span></span> <span data-ttu-id="13fff-113">使用可能な値が含まれます: 'Standard'、'リポジトリ'</span><span class="sxs-lookup"><span data-stu-id="13fff-113">Possible values include: 'Standard', 'Repository'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13fff-114">取得またはホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="13fff-114">Gets or sets hostname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SslState&gt; SslState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SslState&gt; SslState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.SslState" />
      <MemberSignature Language="VB.NET" Value="Public Property SslState As Nullable(Of SslState)" />
      <MemberSignature Language="F#" Value="member this.SslState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SslState&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.SslState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sslState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13fff-115">取得または SSL の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="13fff-115">Gets or sets SSL type.</span></span> <span data-ttu-id="13fff-116">使用可能な値が含まれます: '無効'、'SniEnabled'、'IpBasedEnabled'</span><span class="sxs-lookup"><span data-stu-id="13fff-116">Possible values include: 'Disabled', 'SniEnabled', 'IpBasedEnabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13fff-117">取得または SSL 証明書の拇印を設定します。</span><span class="sxs-lookup"><span data-stu-id="13fff-117">Gets or sets SSL certificate thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToUpdate">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ToUpdate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ToUpdate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.ToUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Property ToUpdate As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ToUpdate : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.ToUpdate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="toUpdate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13fff-118">取得または設定セット&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; 既存のホスト名を更新します。</span><span class="sxs-lookup"><span data-stu-id="13fff-118">Gets or sets set to &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to update existing hostname.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualIP">
      <MemberSignature Language="C#" Value="public string VirtualIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.VirtualIP" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualIP As String" />
      <MemberSignature Language="F#" Value="member this.VirtualIP : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState.VirtualIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13fff-119">取得または設定の IP ベースの SSL の場合は、ホスト名に割り当てられている仮想 IP アドレスが有効にします。</span><span class="sxs-lookup"><span data-stu-id="13fff-119">Gets or sets virtual IP address assigned to the hostname if IP based SSL is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>