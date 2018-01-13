<Type Name="TopicTypeInfo" FullName="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo">
  <TypeSignature Language="C#" Value="public class TopicTypeInfo : Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopicTypeInfo extends Microsoft.Azure.Management.EventGrid.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class TopicTypeInfo&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type TopicTypeInfo = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventGrid.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a65d4-101">トピックのプロパティは、情報を入力します。</span><span class="sxs-lookup"><span data-stu-id="a65d4-101">Properties of a topic type info.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicTypeInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a65d4-102">TopicTypeInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a65d4-102">Initializes a new instance of the TopicTypeInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicTypeInfo (string id = null, string name = null, string type = null, string provider = null, string displayName = null, string description = null, string resourceRegionType = null, string provisioningState = null, System.Collections.Generic.IList&lt;string&gt; supportedLocations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string provider, string displayName, string description, string resourceRegionType, string provisioningState, class System.Collections.Generic.IList`1&lt;string&gt; supportedLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional provider As String = null, Optional displayName As String = null, Optional description As String = null, Optional resourceRegionType As String = null, Optional provisioningState As String = null, Optional supportedLocations As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo : string * string * string * string * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo" Usage="new Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo (id, name, type, provider, displayName, description, resourceRegionType, provisioningState, supportedLocations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="resourceRegionType" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="supportedLocations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="a65d4-103">リソースの完全修飾識別子</span><span class="sxs-lookup"><span data-stu-id="a65d4-103">Fully qualified identifier of the resource</span></span></param>
        <param name="name"><span data-ttu-id="a65d4-104">リソースの名前</span><span class="sxs-lookup"><span data-stu-id="a65d4-104">Name of the resource</span></span></param>
        <param name="type"><span data-ttu-id="a65d4-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="a65d4-105">Type of the resource</span></span></param>
        <param name="provider"><span data-ttu-id="a65d4-106">トピックの種類のプロバイダーの Namespace です。</span><span class="sxs-lookup"><span data-stu-id="a65d4-106">Namespace of the provider of the topic type.</span></span></param>
        <param name="displayName"><span data-ttu-id="a65d4-107">トピックの種類の表示名。</span><span class="sxs-lookup"><span data-stu-id="a65d4-107">Display Name for the topic type.</span></span></param>
        <param name="description"><span data-ttu-id="a65d4-108">トピックの種類の説明です。</span><span class="sxs-lookup"><span data-stu-id="a65d4-108">Description of the topic type.</span></span></param>
        <param name="resourceRegionType"><span data-ttu-id="a65d4-109">リソースの領域の種類。</span><span class="sxs-lookup"><span data-stu-id="a65d4-109">Region type of the resource.</span></span>
            <span data-ttu-id="a65d4-110">使用可能な値が含まれます: 'RegionalResource'、'GlobalResource'</span><span class="sxs-lookup"><span data-stu-id="a65d4-110">Possible values include: 'RegionalResource', 'GlobalResource'</span></span></param>
        <param name="provisioningState"><span data-ttu-id="a65d4-111">トピックの種類のプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="a65d4-111">Provisioning state of the topic type.</span></span> <span data-ttu-id="a65d4-112">使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'キャンセル', '失敗'</span><span class="sxs-lookup"><span data-stu-id="a65d4-112">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Canceled', 'Failed'</span></span></param>
        <param name="supportedLocations"><span data-ttu-id="a65d4-113">このトピックの種類でサポートされる場所の一覧です。</span><span class="sxs-lookup"><span data-stu-id="a65d4-113">List of locations supported by this topic type.</span></span></param>
        <summary>
            <span data-ttu-id="a65d4-114">TopicTypeInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a65d4-114">Initializes a new instance of the TopicTypeInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a65d4-115">取得またはトピックの種類の説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="a65d4-115">Gets or sets description of the topic type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a65d4-116">取得または設定は、トピックの種類の名前を表示します。</span><span class="sxs-lookup"><span data-stu-id="a65d4-116">Gets or sets display Name for the topic type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a65d4-117">取得またはトピックの種類のプロバイダーの名前空間を設定します。</span><span class="sxs-lookup"><span data-stu-id="a65d4-117">Gets or sets namespace of the provider of the topic type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
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
            <span data-ttu-id="a65d4-118">取得またはトピックの種類のプロビジョニング状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a65d4-118">Gets or sets provisioning state of the topic type.</span></span> <span data-ttu-id="a65d4-119">使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'キャンセル', '失敗'</span><span class="sxs-lookup"><span data-stu-id="a65d4-119">Possible values include: 'Creating', 'Updating', 'Deleting', 'Succeeded', 'Canceled', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceRegionType">
      <MemberSignature Language="C#" Value="public string ResourceRegionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceRegionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.ResourceRegionType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceRegionType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceRegionType : string with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.ResourceRegionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceRegionType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a65d4-120">取得またはリソースの領域の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="a65d4-120">Gets or sets region type of the resource.</span></span> <span data-ttu-id="a65d4-121">使用可能な値が含まれます: 'RegionalResource'、'GlobalResource'</span><span class="sxs-lookup"><span data-stu-id="a65d4-121">Possible values include: 'RegionalResource', 'GlobalResource'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SupportedLocations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SupportedLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.SupportedLocations" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportedLocations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SupportedLocations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.EventGrid.Models.TopicTypeInfo.SupportedLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportedLocations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a65d4-122">取得またはこのトピックの種類でサポートされる場所の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a65d4-122">Gets or sets list of locations supported by this topic type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>