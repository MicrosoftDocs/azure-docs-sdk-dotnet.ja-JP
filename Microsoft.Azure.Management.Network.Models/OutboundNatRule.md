<Type Name="OutboundNatRule" FullName="Microsoft.Azure.Management.Network.Models.OutboundNatRule">
  <TypeSignature Language="C#" Value="public class OutboundNatRule : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutboundNatRule extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.OutboundNatRule" />
  <TypeSignature Language="VB.NET" Value="Public Class OutboundNatRule&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type OutboundNatRule = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="02a27-101">ロード バランサーの発信 NAT プールです。</span><span class="sxs-lookup"><span data-stu-id="02a27-101">Outbound NAT pool of the load balancer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutboundNatRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.OutboundNatRule.#ctor" />
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
            <span data-ttu-id="02a27-102">OutboundNatRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="02a27-102">Initializes a new instance of the OutboundNatRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutboundNatRule (Microsoft.Azure.Management.Network.Models.SubResource backendAddressPool, string id = null, Nullable&lt;int&gt; allocatedOutboundPorts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; frontendIPConfigurations = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Models.SubResource backendAddressPool, string id, valuetype System.Nullable`1&lt;int32&gt; allocatedOutboundPorts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; frontendIPConfigurations, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.OutboundNatRule.#ctor(Microsoft.Azure.Management.Network.Models.SubResource,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SubResource},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backendAddressPool As SubResource, Optional id As String = null, Optional allocatedOutboundPorts As Nullable(Of Integer) = null, Optional frontendIPConfigurations As IList(Of SubResource) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.OutboundNatRule : Microsoft.Azure.Management.Network.Models.SubResource * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.OutboundNatRule" Usage="new Microsoft.Azure.Management.Network.Models.OutboundNatRule (backendAddressPool, id, allocatedOutboundPorts, frontendIPConfigurations, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backendAddressPool" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="allocatedOutboundPorts" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="frontendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backendAddressPool"><span data-ttu-id="02a27-103">Dip のプールへの参照。</span><span class="sxs-lookup"><span data-stu-id="02a27-103">A reference to a pool of DIPs.</span></span>
            <span data-ttu-id="02a27-104">送信トラフィックは、バックエンド ip アドレスで ip アドレスの間で分散ロードではランダムにです。</span><span class="sxs-lookup"><span data-stu-id="02a27-104">Outbound traffic is randomly load balanced across IPs in the backend IPs.</span></span></param>
        <param name="id"><span data-ttu-id="02a27-105">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="02a27-105">Resource ID.</span></span></param>
        <param name="allocatedOutboundPorts"><span data-ttu-id="02a27-106">Nat の外側に使用する送信ポートの数</span><span class="sxs-lookup"><span data-stu-id="02a27-106">The number of outbound ports to be used for NAT.</span></span></param>
        <param name="frontendIPConfigurations"><span data-ttu-id="02a27-107">ロード バランサーのフロント エンド IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="02a27-107">The Frontend IP addresses of the load balancer.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="02a27-108">パブリック Ip リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="02a27-108">Gets the provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="02a27-109">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="02a27-109">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="02a27-110">リソース グループ内で一意であるリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="02a27-110">The name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="02a27-111">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="02a27-111">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="02a27-112">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="02a27-112">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="02a27-113">OutboundNatRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="02a27-113">Initializes a new instance of the OutboundNatRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocatedOutboundPorts">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AllocatedOutboundPorts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AllocatedOutboundPorts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.OutboundNatRule.AllocatedOutboundPorts" />
      <MemberSignature Language="VB.NET" Value="Public Property AllocatedOutboundPorts As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AllocatedOutboundPorts : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.OutboundNatRule.AllocatedOutboundPorts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocatedOutboundPorts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02a27-114">取得または設定の nat の外側に使用する送信ポートの数</span><span class="sxs-lookup"><span data-stu-id="02a27-114">Gets or sets the number of outbound ports to be used for NAT.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource BackendAddressPool { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource BackendAddressPool" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.OutboundNatRule.BackendAddressPool" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPool As SubResource" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPool : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.OutboundNatRule.BackendAddressPool" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendAddressPool")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02a27-115">取得または Dip のプールへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="02a27-115">Gets or sets a reference to a pool of DIPs.</span></span> <span data-ttu-id="02a27-116">送信トラフィックは、バックエンド ip アドレスで ip アドレスの間で分散ロードではランダムにです。</span><span class="sxs-lookup"><span data-stu-id="02a27-116">Outbound traffic is randomly load balanced across IPs in the backend IPs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.OutboundNatRule.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.OutboundNatRule.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="02a27-117">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="02a27-117">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; FrontendIPConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SubResource&gt; FrontendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.OutboundNatRule.FrontendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfigurations As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.OutboundNatRule.FrontendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02a27-118">取得またはアドレスのロード バランサーのフロント エンド IP を設定します。</span><span class="sxs-lookup"><span data-stu-id="02a27-118">Gets or sets the Frontend IP addresses of the load balancer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.OutboundNatRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.OutboundNatRule.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="02a27-119">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="02a27-119">Gets or sets the name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="02a27-120">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="02a27-120">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.OutboundNatRule.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.OutboundNatRule.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="02a27-121">パブリック Ip リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="02a27-121">Gets the provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="02a27-122">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="02a27-122">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.OutboundNatRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outboundNatRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="02a27-123">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="02a27-123">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="02a27-124">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="02a27-124">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>