<Type Name="Manager" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager">
  <TypeSignature Language="C#" Value="public class Manager : Microsoft.Azure.Management.StorSimple8000Series.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Manager extends Microsoft.Azure.Management.StorSimple8000Series.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager" />
  <TypeSignature Language="VB.NET" Value="Public Class Manager&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Manager = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="02dee-101">StorSimple Manager です。</span><span class="sxs-lookup"><span data-stu-id="02dee-101">The StorSimple Manager.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Manager ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="02dee-102">マネージャー クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="02dee-102">Initializes a new instance of the Manager class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Manager (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings cisIntrinsicSettings = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings cisIntrinsicSettings, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional cisIntrinsicSettings As ManagerIntrinsicSettings = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Manager : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Manager" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Manager (location, id, name, type, tags, cisIntrinsicSettings, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cisIntrinsicSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="02dee-103">リソースの地理的場所。</span><span class="sxs-lookup"><span data-stu-id="02dee-103">The geo location of the resource.</span></span></param>
        <param name="id"><span data-ttu-id="02dee-104">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="02dee-104">The resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="02dee-105">リソース名。</span><span class="sxs-lookup"><span data-stu-id="02dee-105">The resource name.</span></span></param>
        <param name="type"><span data-ttu-id="02dee-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="02dee-106">The resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="02dee-107">リソースに関連付けられたタグ。</span><span class="sxs-lookup"><span data-stu-id="02dee-107">The tags attached to the resource.</span></span></param>
        <param name="cisIntrinsicSettings"><span data-ttu-id="02dee-108">StorSimple Manager の型を表します。</span><span class="sxs-lookup"><span data-stu-id="02dee-108">Represents the type of StorSimple Manager.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="02dee-109">プロビジョニングの取得は、リソースの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="02dee-109">Specifies the state of the resource as it is getting provisioned.</span></span> <span data-ttu-id="02dee-110">「成功」の値は、マネージャーが正常に作成を意味します。</span><span class="sxs-lookup"><span data-stu-id="02dee-110">Value of "Succeeded" means the Manager was successfully created.</span></span></param>
        <param name="etag"><span data-ttu-id="02dee-111">マネージャーの etag です。</span><span class="sxs-lookup"><span data-stu-id="02dee-111">The etag of the manager.</span></span></param>
        <summary>
            <span data-ttu-id="02dee-112">マネージャー クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="02dee-112">Initializes a new instance of the Manager class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CisIntrinsicSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings CisIntrinsicSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings CisIntrinsicSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.CisIntrinsicSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CisIntrinsicSettings As ManagerIntrinsicSettings" />
      <MemberSignature Language="F#" Value="member this.CisIntrinsicSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.CisIntrinsicSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cisIntrinsicSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerIntrinsicSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02dee-113">取得または設定は、StorSimple Manager の種類を表します。</span><span class="sxs-lookup"><span data-stu-id="02dee-113">Gets or sets represents the type of StorSimple Manager.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="02dee-114">取得またはマネージャーの etag を設定します。</span><span class="sxs-lookup"><span data-stu-id="02dee-114">Gets or sets the etag of the manager.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="02dee-115">取得または設定がプロビジョニングされてを取得するリソースの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="02dee-115">Gets or sets specifies the state of the resource as it is getting provisioned.</span></span> <span data-ttu-id="02dee-116">「成功」の値は、マネージャーが正常に作成を意味します。</span><span class="sxs-lookup"><span data-stu-id="02dee-116">Value of "Succeeded" means the Manager was successfully created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerSku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Sku As ManagerSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerSku" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02dee-117">Sku を指定します。</span><span class="sxs-lookup"><span data-stu-id="02dee-117">Specifies the Sku.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Manager.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="manager.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="02dee-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="02dee-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="02dee-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="02dee-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>