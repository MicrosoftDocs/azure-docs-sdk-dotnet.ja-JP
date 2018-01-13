<Type Name="VnetInfoInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner">
  <TypeSignature Language="C#" Value="public class VnetInfoInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VnetInfoInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VnetInfoInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type VnetInfoInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f8a3d-101">仮想ネットワークについてのコントラクト。</span><span class="sxs-lookup"><span data-stu-id="f8a3d-101">Virtual Network information contract.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetInfoInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8a3d-102">VnetInfoInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f8a3d-102">Initializes a new instance of the VnetInfoInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetInfoInner (string id = null, string name = null, string kind = null, string type = null, string vnetResourceId = null, string certThumbprint = null, string certBlob = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; routes = null, Nullable&lt;bool&gt; resyncRequired = null, string dnsServers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string vnetResourceId, string certThumbprint, string certBlob, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; routes, valuetype System.Nullable`1&lt;bool&gt; resyncRequired, string dnsServers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional vnetResourceId As String = null, Optional certThumbprint As String = null, Optional certBlob As String = null, Optional routes As IList(Of VnetRouteInner) = null, Optional resyncRequired As Nullable(Of Boolean) = null, Optional dnsServers As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner : string * string * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner (id, name, kind, type, vnetResourceId, certThumbprint, certBlob, routes, resyncRequired, dnsServers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="vnetResourceId" Type="System.String" />
        <Parameter Name="certThumbprint" Type="System.String" />
        <Parameter Name="certBlob" Type="System.String" />
        <Parameter Name="routes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;" />
        <Parameter Name="resyncRequired" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="dnsServers" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="vnetResourceId">To be added.</param>
        <param name="certThumbprint">To be added.</param>
        <param name="certBlob">To be added.</param>
        <param name="routes">To be added.</param>
        <param name="resyncRequired">To be added.</param>
        <param name="dnsServers">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertBlob">
      <MemberSignature Language="C#" Value="public string CertBlob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertBlob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.CertBlob" />
      <MemberSignature Language="VB.NET" Value="Public Property CertBlob As String" />
      <MemberSignature Language="F#" Value="member this.CertBlob : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.CertBlob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certBlob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8a3d-103">取得またはポイント対サイト VPN 接続の認証に使用する秘密キーの公開キーを含む blob を証明書ファイル (.cer) を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8a3d-103">Gets or sets a certificate file (.cer) blob containing the public key of the private key used to authenticate a Point-To-Site VPN connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertThumbprint">
      <MemberSignature Language="C#" Value="public string CertThumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.CertThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.CertThumbprint : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.CertThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8a3d-104">クライアント証明書の拇印を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8a3d-104">Gets the client certificate thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsServers">
      <MemberSignature Language="C#" Value="public string DnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.DnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsServers As String" />
      <MemberSignature Language="F#" Value="member this.DnsServers : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.DnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8a3d-105">取得または、この仮想ネットワークで使用する DNS サーバーを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8a3d-105">Gets or sets DNS servers to be used by this Virtual Network.</span></span> <span data-ttu-id="f8a3d-106">これには、IP アドレスのコンマ区切りの一覧があります。</span><span class="sxs-lookup"><span data-stu-id="f8a3d-106">This should be a comma-separated list of IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResyncRequired">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ResyncRequired { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ResyncRequired" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.ResyncRequired" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResyncRequired As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ResyncRequired : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.ResyncRequired" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resyncRequired")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8a3d-107">取得&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 再同期が必要な、それ以外の場合&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="f8a3d-107">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if a resync is required; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Routes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; Routes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt; Routes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.Routes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Routes As IList(Of VnetRouteInner)" />
      <MemberSignature Language="F#" Value="member this.Routes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.Routes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VnetRouteInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8a3d-108">この仮想ネットワーク接続で使用するルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="f8a3d-108">Gets the routes that this Virtual Network connection uses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetResourceId">
      <MemberSignature Language="C#" Value="public string VnetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.VnetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.VnetResourceId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner.VnetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8a3d-109">取得または設定、仮想ネットワークのリソース id です。</span><span class="sxs-lookup"><span data-stu-id="f8a3d-109">Gets or sets the Virtual Network's resource ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>