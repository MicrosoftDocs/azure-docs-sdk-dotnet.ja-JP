<Type Name="VpnClientParameters" FullName="Microsoft.Azure.Management.Network.Models.VpnClientParameters">
  <TypeSignature Language="C#" Value="public class VpnClientParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VpnClientParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VpnClientParameters" />
  <TypeSignature Language="F#" Value="type VpnClientParameters = class" />
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
            パッケージの生成で Vpn クライアント パラメーター
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VpnClientParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VpnClientParameters.#ctor" />
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
            VpnClientParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VpnClientParameters (string processorArchitecture = null, string authenticationMethod = null, string radiusServerAuthCertificate = null, System.Collections.Generic.IList&lt;string&gt; clientRootCertificates = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string processorArchitecture, string authenticationMethod, string radiusServerAuthCertificate, class System.Collections.Generic.IList`1&lt;string&gt; clientRootCertificates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VpnClientParameters.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional processorArchitecture As String = null, Optional authenticationMethod As String = null, Optional radiusServerAuthCertificate As String = null, Optional clientRootCertificates As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VpnClientParameters : string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.VpnClientParameters" Usage="new Microsoft.Azure.Management.Network.Models.VpnClientParameters (processorArchitecture, authenticationMethod, radiusServerAuthCertificate, clientRootCertificates)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="processorArchitecture" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="System.String" />
        <Parameter Name="radiusServerAuthCertificate" Type="System.String" />
        <Parameter Name="clientRootCertificates" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="processorArchitecture">VPN クライアントのプロセッサ アーキテクチャです。 使用可能な値が: 'AMD64' および 'X86' です。 使用可能な値が含まれます: 'Amd64'、'X86'</param>
        <param name="authenticationMethod">VPN クライアントの認証方法です。 使用可能な値が: 'EAPTLS' および 'EAPMSCHAPv2' です。 使用可能な値が含まれます: 'EAPTLS'、'EAPMSCHAPv2'</param>
        <param name="radiusServerAuthCertificate">Base 64 として radius サーバー認証証明書の公開証明書データにエンコードされた文字列を指定します。 外部の radius 認証を EAPTLS 認証で構成されているかどうかにのみ必要です。</param>
        <param name="clientRootCertificates">クライアント ルート証明書の公開証明書データの一覧は、Base 64 文字列としてエンコードされます。
            EAPTLS による認証を外部の半径の省略可能なパラメーターに基づいています。</param>
        <summary>
            VpnClientParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationMethod">
      <MemberSignature Language="C#" Value="public string AuthenticationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.AuthenticationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationMethod As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationMethod : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.AuthenticationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authenticationMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または VPN クライアントの認証方法を設定します。 使用可能な値が: 'EAPTLS' および 'EAPMSCHAPv2' です。 使用可能な値が含まれます: 'EAPTLS'、'EAPMSCHAPv2'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRootCertificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ClientRootCertificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ClientRootCertificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.ClientRootCertificates" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRootCertificates As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ClientRootCertificates : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.ClientRootCertificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clientRootCertificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Base 64 文字列としてエンコードされたデータを公開証明書のクライアント ルート証明書の一覧を設定します。 EAPTLS による認証を外部の半径の省略可能なパラメーターに基づいています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessorArchitecture">
      <MemberSignature Language="C#" Value="public string ProcessorArchitecture { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProcessorArchitecture" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.ProcessorArchitecture" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessorArchitecture As String" />
      <MemberSignature Language="F#" Value="member this.ProcessorArchitecture : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.ProcessorArchitecture" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="processorArchitecture")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または VPN クライアントのプロセッサ アーキテクチャを設定します。 使用可能な値が: 'AMD64' および 'X86' です。 使用可能な値が含まれます: 'Amd64'、'X86'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RadiusServerAuthCertificate">
      <MemberSignature Language="C#" Value="public string RadiusServerAuthCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RadiusServerAuthCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VpnClientParameters.RadiusServerAuthCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property RadiusServerAuthCertificate As String" />
      <MemberSignature Language="F#" Value="member this.RadiusServerAuthCertificate : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VpnClientParameters.RadiusServerAuthCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="radiusServerAuthCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または radius サーバーの公開証明書データに base-64 でエンコードされた文字列としての認証証明書を設定します。 外部の radius 認証を EAPTLS 認証で構成されているかどうかにのみ必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>