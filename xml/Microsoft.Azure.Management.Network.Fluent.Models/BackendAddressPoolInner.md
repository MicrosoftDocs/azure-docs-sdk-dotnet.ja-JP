<Type Name="BackendAddressPoolInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner">
  <TypeSignature Language="C#" Value="public class BackendAddressPoolInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackendAddressPoolInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner" />
  <TypeSignature Language="VB.NET" Value="Public Class BackendAddressPoolInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type BackendAddressPoolInner = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="b134f-101">バックエンド IP アドレスのプールです。</span><span class="sxs-lookup"><span data-stu-id="b134f-101">Pool of backend IP addresses.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackendAddressPoolInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b134f-102">BackendAddressPoolInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b134f-102">Initializes a new instance of the BackendAddressPoolInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackendAddressPoolInner (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; backendIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; loadBalancingRules = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource outboundNatRule = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; backendIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; loadBalancingRules, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource outboundNatRule, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner},System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.SubResource},Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional backendIPConfigurations As IList(Of NetworkInterfaceIPConfigurationInner) = null, Optional loadBalancingRules As IList(Of SubResource) = null, Optional outboundNatRule As SubResource = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner (id, backendIPConfigurations, loadBalancingRules, outboundNatRule, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="backendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt;" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" />
        <Parameter Name="outboundNatRule" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="backendIPConfigurations"><span data-ttu-id="b134f-103">ネットワーク インターフェイスで定義されている IP アドレスへの参照のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="b134f-103">Gets collection of references to IP addresses defined in network interfaces.</span></span></param>
        <param name="loadBalancingRules"><span data-ttu-id="b134f-104">このバックエンド アドレス プールを使用するルールを分散ロードを取得します。</span><span class="sxs-lookup"><span data-stu-id="b134f-104">Gets load balancing rules that use this backend address pool.</span></span></param>
        <param name="outboundNatRule"><span data-ttu-id="b134f-105">このバックエンド アドレス プールを使用する送信規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="b134f-105">Gets outbound rules that use this backend address pool.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="b134f-106">パブリック IP リソースの状態のプロビジョニングを取得します。</span><span class="sxs-lookup"><span data-stu-id="b134f-106">Get provisioning state of the public IP resource.</span></span> <span data-ttu-id="b134f-107">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="b134f-107">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="b134f-108">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="b134f-108">Gets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="b134f-109">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="b134f-109">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="b134f-110">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="b134f-110">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="b134f-111">BackendAddressPoolInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b134f-111">Initializes a new instance of the BackendAddressPoolInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; BackendIPConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; BackendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.BackendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendIPConfigurations As IList(Of NetworkInterfaceIPConfigurationInner)" />
      <MemberSignature Language="F#" Value="member this.BackendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.BackendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b134f-112">ネットワーク インターフェイスで定義されている IP アドレスへの参照のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="b134f-112">Gets collection of references to IP addresses defined in network interfaces.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.Etag" />
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
            <span data-ttu-id="b134f-113">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="b134f-113">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; LoadBalancingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancingRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.LoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b134f-114">このバックエンド アドレス プールを使用するルールを分散ロードを取得します。</span><span class="sxs-lookup"><span data-stu-id="b134f-114">Gets load balancing rules that use this backend address pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.Name" />
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
            <span data-ttu-id="b134f-115">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="b134f-115">Gets name of the resource that is unique within a resource group.</span></span>
            <span data-ttu-id="b134f-116">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="b134f-116">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource OutboundNatRule { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource OutboundNatRule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.OutboundNatRule" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundNatRule As SubResource" />
      <MemberSignature Language="F#" Value="member this.OutboundNatRule : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.OutboundNatRule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundNatRule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b134f-117">このバックエンド アドレス プールを使用する送信規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="b134f-117">Gets outbound rules that use this backend address pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BackendAddressPoolInner.ProvisioningState" />
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
            <span data-ttu-id="b134f-118">取得または get、パブリック IP リソースのプロビジョニング状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="b134f-118">Gets or sets get provisioning state of the public IP resource.</span></span>
            <span data-ttu-id="b134f-119">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="b134f-119">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>