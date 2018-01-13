<Type Name="VpnClientConfiguration" FullName="Microsoft.Azure.Management.Network.Models.VpnClientConfiguration">
  <TypeSignature Language="C#" Value="public class VpnClientConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VpnClientConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VpnClientConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VpnClientConfiguration" />
  <TypeSignature Language="F#" Value="type VpnClientConfiguration = class" />
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
            <span data-ttu-id="18273-101">P2S クライアント VpnClientConfiguration です。</span><span class="sxs-lookup"><span data-stu-id="18273-101">VpnClientConfiguration for P2S client.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VpnClientConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.#ctor" />
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
            <span data-ttu-id="18273-102">VpnClientConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="18273-102">Initializes a new instance of the VpnClientConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VpnClientConfiguration (Microsoft.Azure.Management.Network.Models.AddressSpace vpnClientAddressPool = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRootCertificate&gt; vpnClientRootCertificates = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRevokedCertificate&gt; vpnClientRevokedCertificates = null, System.Collections.Generic.IList&lt;string&gt; vpnClientProtocols = null, string radiusServerAddress = null, string radiusServerSecret = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Models.AddressSpace vpnClientAddressPool, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VpnClientRootCertificate&gt; vpnClientRootCertificates, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VpnClientRevokedCertificate&gt; vpnClientRevokedCertificates, class System.Collections.Generic.IList`1&lt;string&gt; vpnClientProtocols, string radiusServerAddress, string radiusServerSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.#ctor(Microsoft.Azure.Management.Network.Models.AddressSpace,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.VpnClientRootCertificate},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.VpnClientRevokedCertificate},System.Collections.Generic.IList{System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional vpnClientAddressPool As AddressSpace = null, Optional vpnClientRootCertificates As IList(Of VpnClientRootCertificate) = null, Optional vpnClientRevokedCertificates As IList(Of VpnClientRevokedCertificate) = null, Optional vpnClientProtocols As IList(Of String) = null, Optional radiusServerAddress As String = null, Optional radiusServerSecret As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VpnClientConfiguration : Microsoft.Azure.Management.Network.Models.AddressSpace * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRootCertificate&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRevokedCertificate&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string -&gt; Microsoft.Azure.Management.Network.Models.VpnClientConfiguration" Usage="new Microsoft.Azure.Management.Network.Models.VpnClientConfiguration (vpnClientAddressPool, vpnClientRootCertificates, vpnClientRevokedCertificates, vpnClientProtocols, radiusServerAddress, radiusServerSecret)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vpnClientAddressPool" Type="Microsoft.Azure.Management.Network.Models.AddressSpace" />
        <Parameter Name="vpnClientRootCertificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRootCertificate&gt;" />
        <Parameter Name="vpnClientRevokedCertificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRevokedCertificate&gt;" />
        <Parameter Name="vpnClientProtocols" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="radiusServerAddress" Type="System.String" />
        <Parameter Name="radiusServerSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vpnClientAddressPool"><span data-ttu-id="18273-103">P2S がない場合のアドレス空間を表すアドレス スペースのリソースの参照です。</span><span class="sxs-lookup"><span data-stu-id="18273-103">The reference of the address space resource which represents Address space for P2S VpnClient.</span></span></param>
        <param name="vpnClientRootCertificates"><span data-ttu-id="18273-104">仮想ネットワーク ゲートウェイの VpnClientRootCertificate します。</span><span class="sxs-lookup"><span data-stu-id="18273-104">VpnClientRootCertificate for virtual network gateway.</span></span></param>
        <param name="vpnClientRevokedCertificates"><span data-ttu-id="18273-105">仮想ネットワーク ゲートウェイの VpnClientRevokedCertificate します。</span><span class="sxs-lookup"><span data-stu-id="18273-105">VpnClientRevokedCertificate for Virtual network gateway.</span></span></param>
        <param name="vpnClientProtocols"><span data-ttu-id="18273-106">仮想ネットワーク ゲートウェイの VpnClientProtocols します。</span><span class="sxs-lookup"><span data-stu-id="18273-106">VpnClientProtocols for Virtual network gateway.</span></span></param>
        <param name="radiusServerAddress"><span data-ttu-id="18273-107">Vpn クライアント接続のため、VirtualNetworkGateway リソースの radius サーバー アドレスのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="18273-107">The radius server address property of the VirtualNetworkGateway resource for vpn client connection.</span></span></param>
        <param name="radiusServerSecret"><span data-ttu-id="18273-108">Vpn クライアント接続のため、VirtualNetworkGateway リソースの radius シークレット プロパティです。</span><span class="sxs-lookup"><span data-stu-id="18273-108">The radius secret property of the VirtualNetworkGateway resource for vpn client connection.</span></span></param>
        <summary>
            <span data-ttu-id="18273-109">VpnClientConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="18273-109">Initializes a new instance of the VpnClientConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RadiusServerAddress">
      <MemberSignature Language="C#" Value="public string RadiusServerAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RadiusServerAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.RadiusServerAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property RadiusServerAddress As String" />
      <MemberSignature Language="F#" Value="member this.RadiusServerAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.RadiusServerAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="radiusServerAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18273-110">取得または VirtualNetworkGateway リソース vpn クライアント接続用の radius サーバー アドレスのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="18273-110">Gets or sets the radius server address property of the VirtualNetworkGateway resource for vpn client connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RadiusServerSecret">
      <MemberSignature Language="C#" Value="public string RadiusServerSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RadiusServerSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.RadiusServerSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property RadiusServerSecret As String" />
      <MemberSignature Language="F#" Value="member this.RadiusServerSecret : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.RadiusServerSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="radiusServerSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18273-111">取得または VirtualNetworkGateway リソース vpn クライアント接続用の radius secret プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="18273-111">Gets or sets the radius secret property of the VirtualNetworkGateway resource for vpn client connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnClientAddressPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.AddressSpace VpnClientAddressPool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.AddressSpace VpnClientAddressPool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.VpnClientAddressPool" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnClientAddressPool As AddressSpace" />
      <MemberSignature Language="F#" Value="member this.VpnClientAddressPool : Microsoft.Azure.Management.Network.Models.AddressSpace with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.VpnClientAddressPool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vpnClientAddressPool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AddressSpace</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18273-112">取得または P2S がない場合のアドレス空間を表すアドレス スペースのリソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="18273-112">Gets or sets the reference of the address space resource which represents Address space for P2S VpnClient.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnClientProtocols">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VpnClientProtocols { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VpnClientProtocols" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.VpnClientProtocols" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnClientProtocols As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VpnClientProtocols : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.VpnClientProtocols" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vpnClientProtocols")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18273-113">取得または仮想ネットワーク ゲートウェイの vpnClientProtocols を設定します。</span><span class="sxs-lookup"><span data-stu-id="18273-113">Gets or sets vpnClientProtocols for Virtual network gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnClientRevokedCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRevokedCertificate&gt; VpnClientRevokedCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VpnClientRevokedCertificate&gt; VpnClientRevokedCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.VpnClientRevokedCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnClientRevokedCertificates As IList(Of VpnClientRevokedCertificate)" />
      <MemberSignature Language="F#" Value="member this.VpnClientRevokedCertificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRevokedCertificate&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.VpnClientRevokedCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vpnClientRevokedCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRevokedCertificate&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18273-114">取得または仮想ネットワーク ゲートウェイの vpnClientRevokedCertificate を設定します。</span><span class="sxs-lookup"><span data-stu-id="18273-114">Gets or sets vpnClientRevokedCertificate for Virtual network gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnClientRootCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRootCertificate&gt; VpnClientRootCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VpnClientRootCertificate&gt; VpnClientRootCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.VpnClientRootCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnClientRootCertificates As IList(Of VpnClientRootCertificate)" />
      <MemberSignature Language="F#" Value="member this.VpnClientRootCertificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRootCertificate&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientConfiguration.VpnClientRootCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vpnClientRootCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VpnClientRootCertificate&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18273-115">取得または仮想ネットワーク ゲートウェイの vpnClientRootCertificate を設定します。</span><span class="sxs-lookup"><span data-stu-id="18273-115">Gets or sets vpnClientRootCertificate for virtual network gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>