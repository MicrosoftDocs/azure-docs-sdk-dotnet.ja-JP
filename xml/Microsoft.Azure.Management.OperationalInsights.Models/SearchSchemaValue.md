<Type Name="SearchSchemaValue" FullName="Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue">
  <TypeSignature Language="C#" Value="public class SearchSchemaValue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchSchemaValue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchSchemaValue" />
  <TypeSignature Language="F#" Value="type SearchSchemaValue = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="46958-101">スキーマの結果の値オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="46958-101">Value object for schema results.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchSchemaValue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="46958-102">SearchSchemaValue クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="46958-102">Initializes a new instance of the SearchSchemaValue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchSchemaValue (bool indexed, bool stored, bool facet, string name = null, string displayName = null, string type = null, System.Collections.Generic.IList&lt;string&gt; ownerType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool indexed, bool stored, bool facet, string name, string displayName, string type, class System.Collections.Generic.IList`1&lt;string&gt; ownerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.#ctor(System.Boolean,System.Boolean,System.Boolean,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (indexed As Boolean, stored As Boolean, facet As Boolean, Optional name As String = null, Optional displayName As String = null, Optional type As String = null, Optional ownerType As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue : bool * bool * bool * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue (indexed, stored, facet, name, displayName, type, ownerType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="indexed" Type="System.Boolean" />
        <Parameter Name="stored" Type="System.Boolean" />
        <Parameter Name="facet" Type="System.Boolean" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="ownerType" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="indexed"><span data-ttu-id="46958-103">フィールドを示すブール値は、フリー テキストとして検索が可能です。</span><span class="sxs-lookup"><span data-stu-id="46958-103">The boolean that indicates the field is searchable as free text.</span></span></param>
        <param name="stored"><span data-ttu-id="46958-104">フィールドが格納されているかどうかを示すブール値。</span><span class="sxs-lookup"><span data-stu-id="46958-104">The boolean that indicates whether or not the field is stored.</span></span></param>
        <param name="facet"><span data-ttu-id="46958-105">フィールドにするためにファセットがかどうかを示すブール値。</span><span class="sxs-lookup"><span data-stu-id="46958-105">The boolean that indicates whether or not the field is a facet.</span></span></param>
        <param name="name"><span data-ttu-id="46958-106">スキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="46958-106">The name of the schema.</span></span></param>
        <param name="displayName"><span data-ttu-id="46958-107">スキーマの表示名。</span><span class="sxs-lookup"><span data-stu-id="46958-107">The display name of the schema.</span></span></param>
        <param name="type"><span data-ttu-id="46958-108">型。</span><span class="sxs-lookup"><span data-stu-id="46958-108">The type.</span></span></param>
        <param name="ownerType"><span data-ttu-id="46958-109">フィールドを含むワークフローの配列です。</span><span class="sxs-lookup"><span data-stu-id="46958-109">The array of workflows containing the field.</span></span></param>
        <summary>
            <span data-ttu-id="46958-110">SearchSchemaValue クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="46958-110">Initializes a new instance of the SearchSchemaValue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46958-111">取得またはスキーマの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="46958-111">Gets or sets the display name of the schema.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Facet">
      <MemberSignature Language="C#" Value="public bool Facet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Facet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Facet" />
      <MemberSignature Language="VB.NET" Value="Public Property Facet As Boolean" />
      <MemberSignature Language="F#" Value="member this.Facet : bool with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Facet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="facet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46958-112">取得またはフィールドにするためにファセットがかどうかを示すブール値を設定します。</span><span class="sxs-lookup"><span data-stu-id="46958-112">Gets or sets the boolean that indicates whether or not the field is a facet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Indexed">
      <MemberSignature Language="C#" Value="public bool Indexed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Indexed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Indexed" />
      <MemberSignature Language="VB.NET" Value="Public Property Indexed As Boolean" />
      <MemberSignature Language="F#" Value="member this.Indexed : bool with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Indexed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46958-113">取得またはフィールドがフリー テキストとして検索が可能であることを示すブール値を設定します。</span><span class="sxs-lookup"><span data-stu-id="46958-113">Gets or sets the boolean that indicates the field is searchable as free text.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
            <span data-ttu-id="46958-114">取得またはスキーマの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="46958-114">Gets or sets the name of the schema.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OwnerType">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; OwnerType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; OwnerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.OwnerType" />
      <MemberSignature Language="VB.NET" Value="Public Property OwnerType As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.OwnerType : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.OwnerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ownerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46958-115">取得またはフィールドを含むワークフローの配列を設定します。</span><span class="sxs-lookup"><span data-stu-id="46958-115">Gets or sets the array of workflows containing the field.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stored">
      <MemberSignature Language="C#" Value="public bool Stored { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Stored" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Stored" />
      <MemberSignature Language="VB.NET" Value="Public Property Stored As Boolean" />
      <MemberSignature Language="F#" Value="member this.Stored : bool with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Stored" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stored")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46958-116">取得またはフィールドが格納されているかどうかを示すブール値を設定します。</span><span class="sxs-lookup"><span data-stu-id="46958-116">Gets or sets the boolean that indicates whether or not the field is stored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46958-117">取得または型を設定します。</span><span class="sxs-lookup"><span data-stu-id="46958-117">Gets or sets the type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchSchemaValue.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="searchSchemaValue.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="46958-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="46958-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="46958-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46958-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>