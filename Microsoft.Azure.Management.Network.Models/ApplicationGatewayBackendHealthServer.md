<Type Name="ApplicationGatewayBackendHealthServer" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayBackendHealthServer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayBackendHealthServer extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayBackendHealthServer" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayBackendHealthServer = class" />
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
            アプリケーション ゲートウェイ backendhealth http 設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHealthServer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer.#ctor" />
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
            ApplicationGatewayBackendHealthServer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayBackendHealthServer (string address = null, Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration ipConfiguration = null, string health = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration ipConfiguration, string health) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer.#ctor(System.String,Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional address As String = null, Optional ipConfiguration As NetworkInterfaceIPConfiguration = null, Optional health As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer : string * Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer (address, ipConfiguration, health)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="ipConfiguration" Type="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" />
        <Parameter Name="health" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">IP アドレスまたはバックエンド サーバーの FQDN です。</param>
        <param name="ipConfiguration">バックエンド サーバーの IP 構成の参照です。</param>
        <param name="health">バックエンド サーバーの正常性。 使用可能な値が含まれます: 'Unknown'、'Up'、'を'、'Partial'、'ドレイン'</param>
        <summary>
            ApplicationGatewayBackendHealthServer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer.Address" />
      <MemberSignature Language="VB.NET" Value="Public Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="address")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックエンド サーバーの IP アドレスまたは FQDN を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Health">
      <MemberSignature Language="C#" Value="public string Health { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Health" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer.Health" />
      <MemberSignature Language="VB.NET" Value="Public Property Health As String" />
      <MemberSignature Language="F#" Value="member this.Health : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer.Health" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="health")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックエンド サーバーの正常性を設定します。 使用可能な値が含まれます: 'Unknown'、'Up'、'を'、'Partial'、'ドレイン'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration IpConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration IpConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer.IpConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property IpConfiguration As NetworkInterfaceIPConfiguration" />
      <MemberSignature Language="F#" Value="member this.IpConfiguration : Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendHealthServer.IpConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックエンド サーバーの IP 構成の参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>