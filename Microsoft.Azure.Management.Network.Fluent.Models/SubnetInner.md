<Type Name="SubnetInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner">
  <TypeSignature Language="C#" Value="public class SubnetInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubnetInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner" />
  <TypeSignature Language="VB.NET" Value="Public Class SubnetInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type SubnetInner = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="44611-101">仮想ネットワーク リソース内のサブネットです。</span><span class="sxs-lookup"><span data-stu-id="44611-101">Subnet in a virtual network resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubnetInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="44611-102">SubnetInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="44611-102">Initializes a new instance of the SubnetInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubnetInner (string id = null, string addressPrefix = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource networkSecurityGroup = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource routeTable = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ServiceEndpointPropertiesFormat&gt; serviceEndpoints = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner&gt; ipConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner&gt; resourceNavigationLinks = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string addressPrefix, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource networkSecurityGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource routeTable, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ServiceEndpointPropertiesFormat&gt; serviceEndpoints, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner&gt; ipConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner&gt; resourceNavigationLinks, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.#ctor(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ServiceEndpointPropertiesFormat},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional addressPrefix As String = null, Optional networkSecurityGroup As SubResource = null, Optional routeTable As SubResource = null, Optional serviceEndpoints As IList(Of ServiceEndpointPropertiesFormat) = null, Optional ipConfigurations As IList(Of IPConfigurationInner) = null, Optional resourceNavigationLinks As IList(Of ResourceNavigationLinkInner) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner : string * string * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ServiceEndpointPropertiesFormat&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner (id, addressPrefix, networkSecurityGroup, routeTable, serviceEndpoints, ipConfigurations, resourceNavigationLinks, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="addressPrefix" Type="System.String" />
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="routeTable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="serviceEndpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ServiceEndpointPropertiesFormat&gt;" />
        <Parameter Name="ipConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner&gt;" />
        <Parameter Name="resourceNavigationLinks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="addressPrefix">To be added.</param>
        <param name="networkSecurityGroup">To be added.</param>
        <param name="routeTable">To be added.</param>
        <param name="serviceEndpoints">To be added.</param>
        <param name="ipConfigurations">To be added.</param>
        <param name="resourceNavigationLinks">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="name">To be added.</param>
        <param name="etag">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressPrefix">
      <MemberSignature Language="C#" Value="public string AddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.AddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.AddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.AddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.addressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44611-103">取得またはサブネットのアドレス プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="44611-103">Gets or sets the address prefix for the subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.Etag" />
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
            <span data-ttu-id="44611-104">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="44611-104">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner&gt; IpConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner&gt; IpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.IpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IpConfigurations As IList(Of IPConfigurationInner)" />
      <MemberSignature Language="F#" Value="member this.IpConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.IpConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.IPConfigurationInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44611-105">サブネットを使用して、ネットワーク インターフェイス IP 構成への参照の配列を取得します。</span><span class="sxs-lookup"><span data-stu-id="44611-105">Gets an array of references to the network interface IP configurations using subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.Name" />
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
            <span data-ttu-id="44611-106">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="44611-106">Gets or sets the name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="44611-107">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="44611-107">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource NetworkSecurityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource NetworkSecurityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.NetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroup As SubResource" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroup : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.NetworkSecurityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkSecurityGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44611-108">取得または NetworkSecurityGroup リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="44611-108">Gets or sets the reference of the NetworkSecurityGroup resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.ProvisioningState" />
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
            <span data-ttu-id="44611-109">取得またはリソースのプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="44611-109">Gets or sets the provisioning state of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceNavigationLinks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner&gt; ResourceNavigationLinks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner&gt; ResourceNavigationLinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.ResourceNavigationLinks" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceNavigationLinks As IList(Of ResourceNavigationLinkInner)" />
      <MemberSignature Language="F#" Value="member this.ResourceNavigationLinks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.ResourceNavigationLinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceNavigationLinks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44611-110">サブネットを使用して外部リソースへの参照の配列を取得します。</span><span class="sxs-lookup"><span data-stu-id="44611-110">Gets an array of references to the external resources using subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource RouteTable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource RouteTable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.RouteTable" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteTable As SubResource" />
      <MemberSignature Language="F#" Value="member this.RouteTable : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.RouteTable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routeTable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44611-111">取得または RouteTable リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="44611-111">Gets or sets the reference of the RouteTable resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ServiceEndpointPropertiesFormat&gt; ServiceEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ServiceEndpointPropertiesFormat&gt; ServiceEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.ServiceEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceEndpoints As IList(Of ServiceEndpointPropertiesFormat)" />
      <MemberSignature Language="F#" Value="member this.ServiceEndpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ServiceEndpointPropertiesFormat&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner.ServiceEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.ServiceEndpointPropertiesFormat&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>