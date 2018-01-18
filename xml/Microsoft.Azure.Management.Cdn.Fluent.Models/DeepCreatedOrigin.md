<Type Name="DeepCreatedOrigin" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin">
  <TypeSignature Language="C#" Value="public class DeepCreatedOrigin" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeepCreatedOrigin extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin" />
  <TypeSignature Language="VB.NET" Value="Public Class DeepCreatedOrigin" />
  <TypeSignature Language="F#" Value="type DeepCreatedOrigin = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7fe32-101">CDN エンドポイントの作成時に追加される元です。</span><span class="sxs-lookup"><span data-stu-id="7fe32-101">Origin to be added when creating a CDN endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeepCreatedOrigin ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7fe32-102">DeepCreatedOrigin クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7fe32-102">Initializes a new instance of the DeepCreatedOrigin class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeepCreatedOrigin (string name, string hostName, Nullable&lt;int&gt; httpPort = null, Nullable&lt;int&gt; httpsPort = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string hostName, valuetype System.Nullable`1&lt;int32&gt; httpPort, valuetype System.Nullable`1&lt;int32&gt; httpsPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.#ctor(System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, hostName As String, Optional httpPort As Nullable(Of Integer) = null, Optional httpsPort As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin : string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin (name, hostName, httpPort, httpsPort)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="httpPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="httpsPort" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7fe32-103">オリジン名</span><span class="sxs-lookup"><span data-stu-id="7fe32-103">Origin name</span></span></param>
        <param name="hostName"><span data-ttu-id="7fe32-104">配信元のアドレス。</span><span class="sxs-lookup"><span data-stu-id="7fe32-104">The address of the origin.</span></span> <span data-ttu-id="7fe32-105">できます、ドメイン名、IPv4 アドレスまたは IPv6 アドレス。</span><span class="sxs-lookup"><span data-stu-id="7fe32-105">It can be a domain names, IPv4 address, or IPv6 address.</span></span></param>
        <param name="httpPort"><span data-ttu-id="7fe32-106">HTTP ポートの値。</span><span class="sxs-lookup"><span data-stu-id="7fe32-106">The value of the HTTP port.</span></span> <span data-ttu-id="7fe32-107">1 ~ 65535 でなければなりません</span><span class="sxs-lookup"><span data-stu-id="7fe32-107">Must be between 1 and 65535</span></span></param>
        <param name="httpsPort"><span data-ttu-id="7fe32-108">HTTPS ポートの値。</span><span class="sxs-lookup"><span data-stu-id="7fe32-108">The value of the HTTPS port.</span></span> <span data-ttu-id="7fe32-109">1 ~ 65535 でなければなりません</span><span class="sxs-lookup"><span data-stu-id="7fe32-109">Must be between 1 and 65535</span></span></param>
        <summary>
            <span data-ttu-id="7fe32-110">DeepCreatedOrigin クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7fe32-110">Initializes a new instance of the DeepCreatedOrigin class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fe32-111">取得または、元のアドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="7fe32-111">Gets or sets the address of the origin.</span></span> <span data-ttu-id="7fe32-112">できます、ドメイン名、IPv4 アドレスまたは IPv6 アドレス。</span><span class="sxs-lookup"><span data-stu-id="7fe32-112">It can be a domain names, IPv4 address, or IPv6 address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; HttpPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; HttpPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.HttpPort" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.HttpPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.HttpPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fe32-113">取得または HTTP ポートの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7fe32-113">Gets or sets the value of the HTTP port.</span></span> <span data-ttu-id="7fe32-114">1 ~ 65535 でなければなりません</span><span class="sxs-lookup"><span data-stu-id="7fe32-114">Must be between 1 and 65535</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpsPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; HttpsPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; HttpsPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.HttpsPort" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpsPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.HttpsPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.HttpsPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpsPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7fe32-115">取得または HTTPS ポートの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7fe32-115">Gets or sets the value of the HTTPS port.</span></span> <span data-ttu-id="7fe32-116">1 ~ 65535 でなければなりません</span><span class="sxs-lookup"><span data-stu-id="7fe32-116">Must be between 1 and 65535</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
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
            <span data-ttu-id="7fe32-117">オリジン名取得または設定</span><span class="sxs-lookup"><span data-stu-id="7fe32-117">Gets or sets origin name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.DeepCreatedOrigin.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deepCreatedOrigin.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7fe32-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7fe32-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7fe32-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7fe32-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>