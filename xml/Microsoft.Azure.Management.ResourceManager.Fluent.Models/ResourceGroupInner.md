<Type Name="ResourceGroupInner" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner">
  <TypeSignature Language="C#" Value="public class ResourceGroupInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceGroupInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceGroupInner" />
  <TypeSignature Language="F#" Value="type ResourceGroupInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="02ba9-101">リソース グループの情報です。</span><span class="sxs-lookup"><span data-stu-id="02ba9-101">Resource group information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceGroupInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="02ba9-102">ResourceGroupInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="02ba9-102">Initializes a new instance of the ResourceGroupInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceGroupInner (string location, string id = null, string name = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupProperties properties = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupProperties properties, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupProperties,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional properties As ResourceGroupProperties = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner : string * string * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupProperties * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner (location, id, name, properties, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupProperties" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="02ba9-103">リソース グループの場所です。</span><span class="sxs-lookup"><span data-stu-id="02ba9-103">The location of the resource group.</span></span> <span data-ttu-id="02ba9-104">これは、リソース グループが作成された後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="02ba9-104">It cannot be changed after the resource group has been created.</span></span> <span data-ttu-id="02ba9-105">米国西部、米国東部、西ヨーロッパ、東アジアなど、サポートされている Azure の場所のいずれかにあります。</span><span class="sxs-lookup"><span data-stu-id="02ba9-105">Has to be one of the supported Azure Locations, such as West US, East US, West Europe, East Asia, etc.</span></span></param>
        <param name="id"><span data-ttu-id="02ba9-106">リソース グループの ID。</span><span class="sxs-lookup"><span data-stu-id="02ba9-106">The ID of the resource group.</span></span></param>
        <param name="name"><span data-ttu-id="02ba9-107">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="02ba9-107">The Name of the resource group.</span></span></param>
        <param name="properties">To be added.</param>
        <param name="tags"><span data-ttu-id="02ba9-108">リソース グループに関連付けられたタグ。</span><span class="sxs-lookup"><span data-stu-id="02ba9-108">The tags attached to the resource group.</span></span></param>
        <summary>
            <span data-ttu-id="02ba9-109">ResourceGroupInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="02ba9-109">Initializes a new instance of the ResourceGroupInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02ba9-110">リソース グループの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="02ba9-110">Gets the ID of the resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02ba9-111">取得またはリソース グループの場所を設定します。</span><span class="sxs-lookup"><span data-stu-id="02ba9-111">Gets or sets the location of the resource group.</span></span> <span data-ttu-id="02ba9-112">これは、リソース グループが作成された後に変更できません。</span><span class="sxs-lookup"><span data-stu-id="02ba9-112">It cannot be changed after the resource group has been created.</span></span> <span data-ttu-id="02ba9-113">米国西部、米国東部、西ヨーロッパ、東アジアなど、サポートされている Azure の場所のいずれかにあります。</span><span class="sxs-lookup"><span data-stu-id="02ba9-113">Has to be one of the supported Azure Locations, such as West US, East US, West Europe, East Asia, etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
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
            <span data-ttu-id="02ba9-114">取得またはリソース グループの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="02ba9-114">Gets or sets the Name of the resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As ResourceGroupProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupProperties with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02ba9-115">取得またはリソース グループに関連付けられたタグを設定します。</span><span class="sxs-lookup"><span data-stu-id="02ba9-115">Gets or sets the tags attached to the resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceGroupInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="02ba9-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="02ba9-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="02ba9-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="02ba9-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>