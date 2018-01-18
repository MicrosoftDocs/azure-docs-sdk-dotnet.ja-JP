<Type Name="ProviderResourceType" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType">
  <TypeSignature Language="C#" Value="public class ProviderResourceType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProviderResourceType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType" />
  <TypeSignature Language="VB.NET" Value="Public Class ProviderResourceType" />
  <TypeSignature Language="F#" Value="type ProviderResourceType = class" />
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
            <span data-ttu-id="49b93-101">リソース プロバイダーによって管理されるリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="49b93-101">Resource type managed by the resource provider.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProviderResourceType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="49b93-102">ProviderResourceType クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="49b93-102">Initializes a new instance of the ProviderResourceType class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProviderResourceType (string resourceType = null, System.Collections.Generic.IList&lt;string&gt; locations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.AliasType&gt; aliases = null, System.Collections.Generic.IList&lt;string&gt; apiVersions = null, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceType, class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.AliasType&gt; aliases, class System.Collections.Generic.IList`1&lt;string&gt; apiVersions, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.Models.AliasType},System.Collections.Generic.IList{System.String},System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceType As String = null, Optional locations As IList(Of String) = null, Optional aliases As IList(Of AliasType) = null, Optional apiVersions As IList(Of String) = null, Optional properties As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType : string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.AliasType&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType (resourceType, locations, aliases, apiVersions, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="aliases" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.AliasType&gt;" />
        <Parameter Name="apiVersions" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="resourceType"><span data-ttu-id="49b93-103">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="49b93-103">The resource type.</span></span></param>
        <param name="locations"><span data-ttu-id="49b93-104">このリソースの種類を作成できる場所のコレクション。</span><span class="sxs-lookup"><span data-stu-id="49b93-104">The collection of locations where this resource type can be created in.</span></span></param>
        <param name="aliases"><span data-ttu-id="49b93-105">このリソースの種類でサポートされているエイリアスです。</span><span class="sxs-lookup"><span data-stu-id="49b93-105">The aliases that are supported by this resource type.</span></span></param>
        <param name="apiVersions"><span data-ttu-id="49b93-106">Api のバージョン。</span><span class="sxs-lookup"><span data-stu-id="49b93-106">The api version.</span></span></param>
        <param name="properties"><span data-ttu-id="49b93-107">プロパティ。</span><span class="sxs-lookup"><span data-stu-id="49b93-107">The properties.</span></span></param>
        <summary>
            <span data-ttu-id="49b93-108">ProviderResourceType クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="49b93-108">Initializes a new instance of the ProviderResourceType class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Aliases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.AliasType&gt; Aliases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.AliasType&gt; Aliases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.Aliases" />
      <MemberSignature Language="VB.NET" Value="Public Property Aliases As IList(Of AliasType)" />
      <MemberSignature Language="F#" Value="member this.Aliases : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.AliasType&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.Aliases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aliases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.AliasType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b93-109">取得またはこのリソースの種類でサポートされているエイリアスを設定します。</span><span class="sxs-lookup"><span data-stu-id="49b93-109">Gets or sets the aliases that are supported by this resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApiVersions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApiVersions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.ApiVersions" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiVersions As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApiVersions : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.ApiVersions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="apiVersions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b93-110">取得または api のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="49b93-110">Gets or sets the api version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.Locations" />
      <MemberSignature Language="VB.NET" Value="Public Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b93-111">取得または設定でこのリソースの種類を作成できる場所の場所のコレクション。</span><span class="sxs-lookup"><span data-stu-id="49b93-111">Gets or sets the collection of locations where this resource type can be created in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.Properties" />
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
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b93-112">取得またはプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="49b93-112">Gets or sets the properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ProviderResourceType.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b93-113">取得またはリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="49b93-113">Gets or sets the resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>