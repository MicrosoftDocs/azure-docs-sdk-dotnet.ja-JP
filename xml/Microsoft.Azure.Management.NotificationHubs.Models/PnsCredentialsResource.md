<Type Name="PnsCredentialsResource" FullName="Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource">
  <TypeSignature Language="C#" Value="public class PnsCredentialsResource : Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PnsCredentialsResource extends Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource" />
  <TypeSignature Language="VB.NET" Value="Public Class PnsCredentialsResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type PnsCredentialsResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.NotificationHubs.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="234b9-101">NotificationHub PNS の説明が資格情報です。</span><span class="sxs-lookup"><span data-stu-id="234b9-101">Description of a NotificationHub PNS Credentials.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PnsCredentialsResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="234b9-102">PnsCredentialsResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="234b9-102">Initializes a new instance of the PnsCredentialsResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PnsCredentialsResource (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null, Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential apnsCredential = null, Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential wnsCredential = null, Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential gcmCredential = null, Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential mpnsCredential = null, Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential admCredential = null, Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential baiduCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku, class Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential apnsCredential, class Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential wnsCredential, class Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential gcmCredential, class Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential mpnsCredential, class Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential admCredential, class Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential baiduCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku,Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential,Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential,Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential,Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential,Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential,Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku * Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential * Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential * Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential * Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential * Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential * Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential -&gt; Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource (location, id, name, type, tags, sku, apnsCredential, wnsCredential, gcmCredential, mpnsCredential, admCredential, baiduCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
        <Parameter Name="apnsCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential" />
        <Parameter Name="wnsCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential" />
        <Parameter Name="gcmCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential" />
        <Parameter Name="mpnsCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential" />
        <Parameter Name="admCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential" />
        <Parameter Name="baiduCredential" Type="Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="234b9-103">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="234b9-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="234b9-104">リソース Id</span><span class="sxs-lookup"><span data-stu-id="234b9-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="234b9-105">リソース名</span><span class="sxs-lookup"><span data-stu-id="234b9-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="234b9-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="234b9-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="234b9-107">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="234b9-107">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="234b9-108">作成された名前空間の sku</span><span class="sxs-lookup"><span data-stu-id="234b9-108">The sku of the created namespace</span></span></param>
        <param name="apnsCredential"><span data-ttu-id="234b9-109">作成された NotificationHub の ApnsCredential</span><span class="sxs-lookup"><span data-stu-id="234b9-109">The ApnsCredential of the created NotificationHub</span></span></param>
        <param name="wnsCredential"><span data-ttu-id="234b9-110">作成された NotificationHub の WnsCredential</span><span class="sxs-lookup"><span data-stu-id="234b9-110">The WnsCredential of the created NotificationHub</span></span></param>
        <param name="gcmCredential"><span data-ttu-id="234b9-111">作成された NotificationHub の GcmCredential</span><span class="sxs-lookup"><span data-stu-id="234b9-111">The GcmCredential of the created NotificationHub</span></span></param>
        <param name="mpnsCredential"><span data-ttu-id="234b9-112">作成された NotificationHub の MpnsCredential</span><span class="sxs-lookup"><span data-stu-id="234b9-112">The MpnsCredential of the created NotificationHub</span></span></param>
        <param name="admCredential"><span data-ttu-id="234b9-113">作成された NotificationHub の AdmCredential</span><span class="sxs-lookup"><span data-stu-id="234b9-113">The AdmCredential of the created NotificationHub</span></span></param>
        <param name="baiduCredential"><span data-ttu-id="234b9-114">作成された NotificationHub の BaiduCredential</span><span class="sxs-lookup"><span data-stu-id="234b9-114">The BaiduCredential of the created NotificationHub</span></span></param>
        <summary>
            <span data-ttu-id="234b9-115">PnsCredentialsResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="234b9-115">Initializes a new instance of the PnsCredentialsResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdmCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential AdmCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential AdmCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.AdmCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property AdmCredential As AdmCredential" />
      <MemberSignature Language="F#" Value="member this.AdmCredential : Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.AdmCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.admCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="234b9-116">取得または作成された NotificationHub の AdmCredential の設定</span><span class="sxs-lookup"><span data-stu-id="234b9-116">Gets or sets the AdmCredential of the created NotificationHub</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential ApnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential ApnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.ApnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property ApnsCredential As ApnsCredential" />
      <MemberSignature Language="F#" Value="member this.ApnsCredential : Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.ApnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.apnsCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.ApnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="234b9-117">取得または作成された NotificationHub の ApnsCredential の設定</span><span class="sxs-lookup"><span data-stu-id="234b9-117">Gets or sets the ApnsCredential of the created NotificationHub</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential BaiduCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential BaiduCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.BaiduCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduCredential As BaiduCredential" />
      <MemberSignature Language="F#" Value="member this.BaiduCredential : Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.BaiduCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.baiduCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.BaiduCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="234b9-118">取得または作成された NotificationHub の BaiduCredential の設定</span><span class="sxs-lookup"><span data-stu-id="234b9-118">Gets or sets the BaiduCredential of the created NotificationHub</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GcmCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential GcmCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential GcmCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.GcmCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property GcmCredential As GcmCredential" />
      <MemberSignature Language="F#" Value="member this.GcmCredential : Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.GcmCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gcmCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.GcmCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="234b9-119">取得または作成された NotificationHub の GcmCredential の設定</span><span class="sxs-lookup"><span data-stu-id="234b9-119">Gets or sets the GcmCredential of the created NotificationHub</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MpnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential MpnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential MpnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.MpnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property MpnsCredential As MpnsCredential" />
      <MemberSignature Language="F#" Value="member this.MpnsCredential : Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.MpnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.mpnsCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.MpnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="234b9-120">取得または作成された NotificationHub の MpnsCredential の設定</span><span class="sxs-lookup"><span data-stu-id="234b9-120">Gets or sets the MpnsCredential of the created NotificationHub</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential WnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential WnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.WnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property WnsCredential As WnsCredential" />
      <MemberSignature Language="F#" Value="member this.WnsCredential : Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.PnsCredentialsResource.WnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.wnsCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="234b9-121">取得または作成された NotificationHub の WnsCredential の設定</span><span class="sxs-lookup"><span data-stu-id="234b9-121">Gets or sets the WnsCredential of the created NotificationHub</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>