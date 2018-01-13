<Type Name="PublicIPAddressDnsSettings" FullName="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings">
  <TypeSignature Language="C#" Value="public class PublicIPAddressDnsSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PublicIPAddressDnsSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class PublicIPAddressDnsSettings" />
  <TypeSignature Language="F#" Value="type PublicIPAddressDnsSettings = class" />
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
            パブリック IP アドレスに関連付けられている DNS レコードの FQDN が含まれています
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicIPAddressDnsSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PublicIPAddressDnsSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicIPAddressDnsSettings (string domainNameLabel = null, string fqdn = null, string reverseFqdn = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string domainNameLabel, string fqdn, string reverseFqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional domainNameLabel As String = null, Optional fqdn As String = null, Optional reverseFqdn As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings : string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings (domainNameLabel, fqdn, reverseFqdn)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="domainNameLabel" Type="System.String" />
        <Parameter Name="fqdn" Type="System.String" />
        <Parameter Name="reverseFqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainNameLabel">取得またはドメイン名ラベルを設定します。ドメイン名ラベルと地域の DNS ゾーンを連結したものでは、パブリック IP アドレスに関連付けられている完全修飾ドメイン名を構成します。 ドメイン名ラベルが指定されている場合、パブリック IP の Microsoft Azure DNS システムで DNS レコードが作成されます。</param>
        <param name="fqdn">パブリック IP に関連付けられている DNS レコードの完全修飾ドメイン名、FQDN を取得します。 これは、domainNameLabel と地域の DNS ゾーンを連結したものです。</param>
        <param name="reverseFqdn">取得または逆方向 FQDN を設定します。 完全修飾したこのパブリック IP アドレスに解決されるドメイン名、ユーザーに表示される、します。 ReverseFqdn を指定すると場合、PTR DNS レコードは、in-addr.arpa ドメイン内の IP アドレスから逆方向 FQDN を指すで作成されます。 </param>
        <summary>
            PublicIPAddressDnsSettings クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainNameLabel">
      <MemberSignature Language="C#" Value="public string DomainNameLabel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainNameLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.DomainNameLabel" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainNameLabel As String" />
      <MemberSignature Language="F#" Value="member this.DomainNameLabel : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.DomainNameLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="domainNameLabel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはドメイン名ラベルを設定します。ドメイン名ラベルと地域の DNS ゾーンを連結したものでは、パブリック IP アドレスに関連付けられている完全修飾ドメイン名を構成します。 ドメイン名ラベルが指定されている場合、パブリック IP の Microsoft Azure DNS システムで DNS レコードが作成されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パブリック IP に関連付けられている DNS レコードの完全修飾ドメイン名、FQDN を取得します。 これは、domainNameLabel と地域の DNS ゾーンを連結したものです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReverseFqdn">
      <MemberSignature Language="C#" Value="public string ReverseFqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReverseFqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.ReverseFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property ReverseFqdn As String" />
      <MemberSignature Language="F#" Value="member this.ReverseFqdn : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressDnsSettings.ReverseFqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reverseFqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または逆方向 FQDN を設定します。 完全修飾したこのパブリック IP アドレスに解決されるドメイン名、ユーザーに表示される、します。 ReverseFqdn を指定すると場合、PTR DNS レコードは、in-addr.arpa ドメイン内の IP アドレスから逆方向 FQDN を指すで作成されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>