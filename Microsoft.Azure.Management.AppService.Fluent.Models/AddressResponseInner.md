<Type Name="AddressResponseInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner">
  <TypeSignature Language="C#" Value="public class AddressResponseInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AddressResponseInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner" />
  <TypeSignature Language="VB.NET" Value="Public Class AddressResponseInner" />
  <TypeSignature Language="F#" Value="type AddressResponseInner = class" />
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
            <span data-ttu-id="bebd5-101">メインのパブリック IP アドレスと、余分な仮想 ip アドレスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="bebd5-101">Describes main public IP address and any extra virtual IPs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AddressResponseInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bebd5-102">AddressResponseInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bebd5-102">Initializes a new instance of the AddressResponseInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AddressResponseInner (string serviceIpAddress = null, string internalIpAddress = null, System.Collections.Generic.IList&lt;string&gt; outboundIpAddresses = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; vipMappings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceIpAddress, string internalIpAddress, class System.Collections.Generic.IList`1&lt;string&gt; outboundIpAddresses, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; vipMappings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceIpAddress As String = null, Optional internalIpAddress As String = null, Optional outboundIpAddresses As IList(Of String) = null, Optional vipMappings As IList(Of VirtualIPMapping) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner (serviceIpAddress, internalIpAddress, outboundIpAddresses, vipMappings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceIpAddress" Type="System.String" />
        <Parameter Name="internalIpAddress" Type="System.String" />
        <Parameter Name="outboundIpAddresses" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="vipMappings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceIpAddress"><span data-ttu-id="bebd5-103">メインのパブリック仮想 IP。</span><span class="sxs-lookup"><span data-stu-id="bebd5-103">Main public virtual IP.</span></span></param>
        <param name="internalIpAddress"><span data-ttu-id="bebd5-104">仮想ネットワーク内部の IP アドレス、App Service 環境の内部負荷分散モードである場合。</span><span class="sxs-lookup"><span data-stu-id="bebd5-104">Virtual Network internal IP address of the App Service Environment if it is in internal load-balancing mode.</span></span></param>
        <param name="outboundIpAddresses"><span data-ttu-id="bebd5-105">発信接続上に表示される IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="bebd5-105">IP addresses appearing on outbound connections.</span></span></param>
        <param name="vipMappings"><span data-ttu-id="bebd5-106">仮想 Ip を追加します。</span><span class="sxs-lookup"><span data-stu-id="bebd5-106">Additional virtual IPs.</span></span></param>
        <summary>
            <span data-ttu-id="bebd5-107">AddressResponseInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bebd5-107">Initializes a new instance of the AddressResponseInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalIpAddress">
      <MemberSignature Language="C#" Value="public string InternalIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner.InternalIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.InternalIpAddress : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner.InternalIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bebd5-108">取得または内部の負荷分散モードである場合に、仮想ネットワークの内部 IP アドレス App Service 環境を設定します。</span><span class="sxs-lookup"><span data-stu-id="bebd5-108">Gets or sets virtual Network internal IP address of the App Service Environment if it is in internal load-balancing mode.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundIpAddresses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; OutboundIpAddresses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; OutboundIpAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner.OutboundIpAddresses" />
      <MemberSignature Language="VB.NET" Value="Public Property OutboundIpAddresses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.OutboundIpAddresses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner.OutboundIpAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outboundIpAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bebd5-109">取得または送信接続上に表示される IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="bebd5-109">Gets or sets IP addresses appearing on outbound connections.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceIpAddress">
      <MemberSignature Language="C#" Value="public string ServiceIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner.ServiceIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.ServiceIpAddress : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner.ServiceIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bebd5-110">取得またはメインのパブリック仮想 IP を設定します。</span><span class="sxs-lookup"><span data-stu-id="bebd5-110">Gets or sets main public virtual IP.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VipMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; VipMappings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; VipMappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner.VipMappings" />
      <MemberSignature Language="VB.NET" Value="Public Property VipMappings As IList(Of VirtualIPMapping)" />
      <MemberSignature Language="F#" Value="member this.VipMappings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AddressResponseInner.VipMappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vipMappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bebd5-111">取得または追加の仮想 Ip を設定します。</span><span class="sxs-lookup"><span data-stu-id="bebd5-111">Gets or sets additional virtual IPs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>