<Type Name="VnetGateway" FullName="Microsoft.Azure.Management.WebSites.Models.VnetGateway">
  <TypeSignature Language="C#" Value="public class VnetGateway : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VnetGateway extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.VnetGateway" />
  <TypeSignature Language="VB.NET" Value="Public Class VnetGateway&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type VnetGateway = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            仮想ネットワーク ゲートウェイのコントラクト。 仮想ネットワーク ゲートウェイを実行できるように VPN パッケージに使用されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetGateway ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetGateway.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VnetGateway クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetGateway (string id = null, string name = null, string kind = null, string type = null, string vnetName = null, string vpnPackageUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string vnetName, string vpnPackageUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetGateway.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional vnetName As String = null, Optional vpnPackageUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.VnetGateway : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.VnetGateway" Usage="new Microsoft.Azure.Management.WebSites.Models.VnetGateway (id, name, kind, type, vnetName, vpnPackageUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="vpnPackageUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="vnetName">仮想ネットワーク名です。</param>
        <param name="vpnPackageUri">VPN パッケージのダウンロード場所の URI。</param>
        <summary>
            VnetGateway クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetName">
      <MemberSignature Language="C#" Value="public string VnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetGateway.VnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetGateway.VnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または仮想ネットワーク名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnPackageUri">
      <MemberSignature Language="C#" Value="public string VpnPackageUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VpnPackageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetGateway.VpnPackageUri" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnPackageUri As String" />
      <MemberSignature Language="F#" Value="member this.VpnPackageUri : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetGateway.VpnPackageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vpnPackageUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または VPN パッケージのダウンロード場所の URI を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>