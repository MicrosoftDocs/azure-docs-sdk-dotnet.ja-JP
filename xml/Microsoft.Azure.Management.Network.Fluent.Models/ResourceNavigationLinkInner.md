<Type Name="ResourceNavigationLinkInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner">
  <TypeSignature Language="C#" Value="public class ResourceNavigationLinkInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceNavigationLinkInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceNavigationLinkInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ResourceNavigationLinkInner = class&#xA;    inherit SubResource" />
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
            <span data-ttu-id="60073-101">ResourceNavigationLink リソースです。</span><span class="sxs-lookup"><span data-stu-id="60073-101">ResourceNavigationLink resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceNavigationLinkInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="60073-102">ResourceNavigationLinkInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="60073-102">Initializes a new instance of the ResourceNavigationLinkInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceNavigationLinkInner (string id = null, string linkedResourceType = null, string link = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string linkedResourceType, string link, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional linkedResourceType As String = null, Optional link As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner (id, linkedResourceType, link, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="linkedResourceType" Type="System.String" />
        <Parameter Name="link" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="linkedResourceType"><span data-ttu-id="60073-103">リンクされたリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="60073-103">Resource type of the linked resource.</span></span></param>
        <param name="link"><span data-ttu-id="60073-104">外部リソースへのリンクします。</span><span class="sxs-lookup"><span data-stu-id="60073-104">Link to the external resource</span></span></param>
        <param name="provisioningState"><span data-ttu-id="60073-105">ResourceNavigationLink リソースのプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="60073-105">Provisioning state of the ResourceNavigationLink resource.</span></span></param>
        <param name="name"><span data-ttu-id="60073-106">リソース グループ内で一意であるリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="60073-106">Name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="60073-107">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="60073-107">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="60073-108">読み取り専用する一意の文字列リソースを更新するたびに変化します。</span><span class="sxs-lookup"><span data-stu-id="60073-108">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="60073-109">ResourceNavigationLinkInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="60073-109">Initializes a new instance of the ResourceNavigationLinkInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.Etag" />
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
            <span data-ttu-id="60073-110">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="60073-110">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Link">
      <MemberSignature Language="C#" Value="public string Link { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Link" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.Link" />
      <MemberSignature Language="VB.NET" Value="Public Property Link As String" />
      <MemberSignature Language="F#" Value="member this.Link : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.Link" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.link")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60073-111">取得または外部のリソースへのリンクの設定</span><span class="sxs-lookup"><span data-stu-id="60073-111">Gets or sets link to the external resource</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedResourceType">
      <MemberSignature Language="C#" Value="public string LinkedResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.LinkedResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedResourceType As String" />
      <MemberSignature Language="F#" Value="member this.LinkedResourceType : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.LinkedResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedResourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60073-112">取得またはリンクされたリソースのリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="60073-112">Gets or sets resource type of the linked resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.Name" />
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
            <span data-ttu-id="60073-113">取得またはリソース グループ内で一意であるリソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="60073-113">Gets or sets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="60073-114">この名前は、リソースへのアクセスに使用できます。</span><span class="sxs-lookup"><span data-stu-id="60073-114">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ResourceNavigationLinkInner.ProvisioningState" />
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
            <span data-ttu-id="60073-115">ResourceNavigationLink リソースの状態のプロビジョニングを取得します。</span><span class="sxs-lookup"><span data-stu-id="60073-115">Gets provisioning state of the ResourceNavigationLink resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>