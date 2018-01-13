<Type Name="NetworkSettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings">
  <TypeSignature Language="C#" Value="public class NetworkSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSettings extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSettings&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type NetworkSettings = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="23079-101">デバイスのネットワーク設定を表します。</span><span class="sxs-lookup"><span data-stu-id="23079-101">Represents the network settings of a device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23079-102">NetworkSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23079-102">Initializes a new instance of the NetworkSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSettings (Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings dnsSettings, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList networkAdapters, Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings webproxySettings, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings dnsSettings, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList networkAdapters, class Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings webproxySettings, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList,Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList * Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings (dnsSettings, networkAdapters, webproxySettings, id, name, type, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings" />
        <Parameter Name="networkAdapters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList" />
        <Parameter Name="webproxySettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="dnsSettings"><span data-ttu-id="23079-103">デバイスの DNS (ドメイン ネーム システム) 設定します。</span><span class="sxs-lookup"><span data-stu-id="23079-103">The DNS (Domain Name System) settings of device.</span></span></param>
        <param name="networkAdapters"><span data-ttu-id="23079-104">デバイスのネットワーク アダプターの一覧です。</span><span class="sxs-lookup"><span data-stu-id="23079-104">The network adapter list of device.</span></span></param>
        <param name="webproxySettings"><span data-ttu-id="23079-105">デバイスのため、webproxy 設定します。</span><span class="sxs-lookup"><span data-stu-id="23079-105">The webproxy settings of device.</span></span></param>
        <param name="id"><span data-ttu-id="23079-106">オブジェクトを一意に識別するパス ID です。</span><span class="sxs-lookup"><span data-stu-id="23079-106">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="23079-107">オブジェクトの名前。</span><span class="sxs-lookup"><span data-stu-id="23079-107">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="23079-108">オブジェクトの階層型です。</span><span class="sxs-lookup"><span data-stu-id="23079-108">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="23079-109">オブジェクトの種類。</span><span class="sxs-lookup"><span data-stu-id="23079-109">The Kind of the object.</span></span> <span data-ttu-id="23079-110">現在は Series8000 はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="23079-110">Currently only Series8000 is supported.</span></span> <span data-ttu-id="23079-111">使用可能な値が含まれます: 'Series8000'</span><span class="sxs-lookup"><span data-stu-id="23079-111">Possible values include: 'Series8000'</span></span></param>
        <summary>
            <span data-ttu-id="23079-112">NetworkSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23079-112">Initializes a new instance of the NetworkSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As DNSSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23079-113">取得またはデバイスの DNS (ドメイン ネーム システム) の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="23079-113">Gets or sets the DNS (Domain Name System) settings of device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkAdapters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList NetworkAdapters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList NetworkAdapters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.NetworkAdapters" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkAdapters As NetworkAdapterList" />
      <MemberSignature Language="F#" Value="member this.NetworkAdapters : Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.NetworkAdapters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAdapters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23079-114">取得またはデバイスのネットワーク アダプターの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="23079-114">Gets or sets the network adapter list of device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23079-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="23079-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="23079-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="23079-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WebproxySettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings WebproxySettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings WebproxySettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.WebproxySettings" />
      <MemberSignature Language="VB.NET" Value="Public Property WebproxySettings As WebproxySettings" />
      <MemberSignature Language="F#" Value="member this.WebproxySettings : Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettings.WebproxySettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.webproxySettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23079-117">取得またはデバイスのため、webproxy 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="23079-117">Gets or sets the webproxy settings of device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>