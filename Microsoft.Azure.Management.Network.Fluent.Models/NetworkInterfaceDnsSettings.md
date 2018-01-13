<Type Name="NetworkInterfaceDnsSettings" FullName="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings">
  <TypeSignature Language="C#" Value="public class NetworkInterfaceDnsSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterfaceDnsSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterfaceDnsSettings" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceDnsSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ネットワーク インターフェイスの DNS 設定。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceDnsSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            NetworkInterfaceDnsSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceDnsSettings (System.Collections.Generic.IList&lt;string&gt; dnsServers = null, System.Collections.Generic.IList&lt;string&gt; appliedDnsServers = null, string internalDnsNameLabel = null, string internalFqdn = null, string internalDomainNameSuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; dnsServers, class System.Collections.Generic.IList`1&lt;string&gt; appliedDnsServers, string internalDnsNameLabel, string internalFqdn, string internalDomainNameSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dnsServers As IList(Of String) = null, Optional appliedDnsServers As IList(Of String) = null, Optional internalDnsNameLabel As String = null, Optional internalFqdn As String = null, Optional internalDomainNameSuffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings (dnsServers, appliedDnsServers, internalDnsNameLabel, internalFqdn, internalDomainNameSuffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dnsServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="appliedDnsServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="internalDnsNameLabel" Type="System.String" />
        <Parameter Name="internalFqdn" Type="System.String" />
        <Parameter Name="internalDomainNameSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dnsServers">DNS サーバーの IP アドレスの一覧です。 Azure に切り替えるには、使用する 'は AzureProvidedDNS' には、DNS 解決が用意されています。
            'AzureProvidedDNS' の値は、他の ip アドレスと組み合わせることはできません、dnsServers コレクション内の値のみをする必要があります。</param>
        <param name="appliedDnsServers">この NIC を使用する VM が可用性セットの一部である場合は、この一覧は、可用性セットの一部であるすべての Nic からのすべての DNS サーバーの和集合があります。 このプロパティは、各 Vm 上に構成されました。</param>
        <param name="internalDnsNameLabel">同じ仮想ネットワーク内の Vm 間の内部通信に使用されるこの NIC の相対的な DNS 名。</param>
        <param name="internalFqdn">完全修飾 DNS 名が同じ仮想ネットワーク内の Vm 間の内部通信をサポートします。</param>
        <param name="internalDomainNameSuffix">InternalDnsNameLabel が指定されていない場合でも、プライマリ仮想マシンの NIC の DNS エントリが作成されます。 この DNS 名は、internalDomainNameSuffix の値は、VM の名前を連結して作成できます。</param>
        <summary>
            NetworkInterfaceDnsSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppliedDnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AppliedDnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AppliedDnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.AppliedDnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property AppliedDnsServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AppliedDnsServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.AppliedDnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="appliedDnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはの場合、この一覧は、可用性セットの一部であるすべての Nic からのすべての DNS サーバーの和集合に、この NIC を使用する VM を可用性セットの一部である場合を設定します。 このプロパティは、各 Vm 上に構成されました。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.DnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DnsServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.DnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または DNS サーバーの IP アドレスの一覧を設定します。 Azure に切り替えるには、使用する 'は AzureProvidedDNS' には、DNS 解決が用意されています。
            'AzureProvidedDNS' の値は、他の ip アドレスと組み合わせることはできません、dnsServers コレクション内の値のみをする必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDnsNameLabel">
      <MemberSignature Language="C#" Value="public string InternalDnsNameLabel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDnsNameLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.InternalDnsNameLabel" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalDnsNameLabel As String" />
      <MemberSignature Language="F#" Value="member this.InternalDnsNameLabel : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.InternalDnsNameLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalDnsNameLabel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または同じ仮想ネットワーク内の Vm 間の内部通信に使用される NIC がこの相対 DNS 名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDomainNameSuffix">
      <MemberSignature Language="C#" Value="public string InternalDomainNameSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDomainNameSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.InternalDomainNameSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalDomainNameSuffix As String" />
      <MemberSignature Language="F#" Value="member this.InternalDomainNameSuffix : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.InternalDomainNameSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalDomainNameSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の VM のプライマリ NIC の DNS エントリが作成された internalDnsNameLabel が指定されていない場合でもです。 この DNS 名は、internalDomainNameSuffix の値は、VM の名前を連結して作成できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalFqdn">
      <MemberSignature Language="C#" Value="public string InternalFqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalFqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.InternalFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalFqdn As String" />
      <MemberSignature Language="F#" Value="member this.InternalFqdn : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings.InternalFqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalFqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または同じ仮想ネットワーク内の Vm 間の内部通信をサポートする完全修飾 DNS 名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>