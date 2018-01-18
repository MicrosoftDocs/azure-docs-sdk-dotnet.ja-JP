<Type Name="ExpressRouteCircuitAuthorizationInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitAuthorizationInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitAuthorizationInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitAuthorizationInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitAuthorizationInner = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="f0a30-101">ExpressRouteCircuit リソースを承認します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-101">Authorization in an ExpressRouteCircuit resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitAuthorizationInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f0a30-102">ExpressRouteCircuitAuthorizationInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-102">Initializes a new instance of the ExpressRouteCircuitAuthorizationInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitAuthorizationInner (string id = null, string authorizationKey = null, string authorizationUseStatus = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string authorizationKey, string authorizationUseStatus, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional authorizationKey As String = null, Optional authorizationUseStatus As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner (id, authorizationKey, authorizationUseStatus, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="authorizationKey" Type="System.String" />
        <Parameter Name="authorizationUseStatus" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="authorizationKey"><span data-ttu-id="f0a30-103">認証キー。</span><span class="sxs-lookup"><span data-stu-id="f0a30-103">The authorization key.</span></span></param>
        <param name="authorizationUseStatus"><span data-ttu-id="f0a30-104">AuthorizationUseStatus です。</span><span class="sxs-lookup"><span data-stu-id="f0a30-104">AuthorizationUseStatus.</span></span>
            <span data-ttu-id="f0a30-105">使用可能な値が: '可能' と '使用中' です。</span><span class="sxs-lookup"><span data-stu-id="f0a30-105">Possible values are: 'Available' and 'InUse'.</span></span> <span data-ttu-id="f0a30-106">使用可能な値が含まれます使用可能'、'使用中'。</span><span class="sxs-lookup"><span data-stu-id="f0a30-106">Possible values include: 'Available', 'InUse'</span></span></param>
        <param name="provisioningState"><span data-ttu-id="f0a30-107">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-107">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="f0a30-108">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="f0a30-108">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="f0a30-109">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-109">Gets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="f0a30-110">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="f0a30-110">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="f0a30-111">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-111">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="f0a30-112">ExpressRouteCircuitAuthorizationInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-112">Initializes a new instance of the ExpressRouteCircuitAuthorizationInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationKey">
      <MemberSignature Language="C#" Value="public string AuthorizationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.AuthorizationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationKey As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationKey : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.AuthorizationKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authorizationKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a30-113">取得または認証キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-113">Gets or sets the authorization key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationUseStatus">
      <MemberSignature Language="C#" Value="public string AuthorizationUseStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationUseStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.AuthorizationUseStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationUseStatus As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationUseStatus : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.AuthorizationUseStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authorizationUseStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a30-114">取得または authorizationUseStatus を設定します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-114">Gets or sets authorizationUseStatus.</span></span> <span data-ttu-id="f0a30-115">使用可能な値が: '可能' と '使用中' です。</span><span class="sxs-lookup"><span data-stu-id="f0a30-115">Possible values are: 'Available' and 'InUse'.</span></span> <span data-ttu-id="f0a30-116">使用可能な値が含まれます使用可能'、'使用中'。</span><span class="sxs-lookup"><span data-stu-id="f0a30-116">Possible values include: 'Available', 'InUse'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.Etag" />
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
            <span data-ttu-id="f0a30-117">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-117">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.Name" />
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
            <span data-ttu-id="f0a30-118">リソース グループ内で一意であるリソースの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-118">Gets name of the resource that is unique within a resource group.</span></span>
            <span data-ttu-id="f0a30-119">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="f0a30-119">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner.ProvisioningState" />
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
            <span data-ttu-id="f0a30-120">パブリック IP リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0a30-120">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="f0a30-121">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="f0a30-121">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>