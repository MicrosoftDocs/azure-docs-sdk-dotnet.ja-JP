<Type Name="IPConfigurationInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner">
  <TypeSignature Language="C#" Value="public class IPConfigurationInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IPConfigurationInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner" />
  <TypeSignature Language="VB.NET" Value="Public Class IPConfigurationInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type IPConfigurationInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Ip 構成
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPConfigurationInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            IPConfigurationInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPConfigurationInner (string id = null, string privateIPAddress = null, string privateIPAllocationMethod = null, Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner subnet = null, Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner publicIPAddress = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string privateIPAddress, string privateIPAllocationMethod, class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner subnet, class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner publicIPAddress, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner,Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional privateIPAddress As String = null, Optional privateIPAllocationMethod As String = null, Optional subnet As SubnetInner = null, Optional publicIPAddress As PublicIPAddressInner = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner : string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner * Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner (id, privateIPAddress, privateIPAllocationMethod, subnet, publicIPAddress, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="privateIPAddress" Type="System.String" />
        <Parameter Name="privateIPAllocationMethod" Type="System.String" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner" />
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="privateIPAddress">IP 構成のプライベート IP アドレス。</param>
        <param name="privateIPAllocationMethod">プライベート IP の割り当て方法です。 可能な値は 'Static' および 'Dynamic' です。 使用可能な値が含まれます: 'Static'、'Dynamic'</param>
        <param name="subnet">サブネットのリソースの参照です。</param>
        <param name="publicIPAddress">パブリック IP リソースの参照です。</param>
        <param name="provisioningState">パブリック IP リソースのプロビジョニングの状態を取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="name">リソース グループ内で一意であるリソースの名前。 この名前は、リソースへのアクセスに使用できます。</param>
        <param name="etag">読み取り専用する一意の文字列リソースを更新するたびに変化します。</param>
        <summary>
            IPConfigurationInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            取得またはリソース グループ内で一意であるリソースの名前を設定します。 この名前は、リソースへのアクセスに使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAddress">
      <MemberSignature Language="C#" Value="public string PrivateIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.PrivateIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.PrivateIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または IP 構成のプライベート IP アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAllocationMethod">
      <MemberSignature Language="C#" Value="public string PrivateIPAllocationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAllocationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.PrivateIPAllocationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAllocationMethod As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAllocationMethod : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.PrivateIPAllocationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAllocationMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプライベート IP の割り当て方法を設定します。 可能な値は 'Static' および 'Dynamic' です。 使用可能な値が含まれます: 'Static'、'Dynamic'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パブリック IP リソースのプロビジョニングの状態を取得します。 使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner PublicIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner PublicIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.PublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddress As PublicIPAddressInner" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddress : Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.PublicIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.PublicIPAddressInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパブリック IP リソースへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As SubnetInner" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブネットのリソースへの参照を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>