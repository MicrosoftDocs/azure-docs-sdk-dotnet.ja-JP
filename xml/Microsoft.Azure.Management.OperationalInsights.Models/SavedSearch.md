<Type Name="SavedSearch" FullName="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch">
  <TypeSignature Language="C#" Value="public class SavedSearch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SavedSearch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch" />
  <TypeSignature Language="VB.NET" Value="Public Class SavedSearch" />
  <TypeSignature Language="F#" Value="type SavedSearch = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ea567-101">保存された検索結果の値オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="ea567-101">Value object for saved search results.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SavedSearch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ea567-102">Savedsearch でクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea567-102">Initializes a new instance of the SavedSearch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SavedSearch (string category, string displayName, string query, long version, string id = null, string etag = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string category, string displayName, string query, int64 version, string id, string etag, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.#ctor(System.String,System.String,System.String,System.Int64,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.OperationalInsights.Models.Tag})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (category As String, displayName As String, query As String, version As Long, Optional id As String = null, Optional etag As String = null, Optional tags As IList(Of Tag) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch : string * string * string * int64 * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch (category, displayName, query, version, id, etag, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="category" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt;" />
      </Parameters>
      <Docs>
        <param name="category"><span data-ttu-id="ea567-103">保存された検索のカテゴリ。</span><span class="sxs-lookup"><span data-stu-id="ea567-103">The category of the saved search.</span></span> <span data-ttu-id="ea567-104">これにより、保存済み検索を高速検索をユーザーにします。</span><span class="sxs-lookup"><span data-stu-id="ea567-104">This helps the user to find a saved search faster.</span></span> </param>
        <param name="displayName"><span data-ttu-id="ea567-105">表示名の検索を保存します。</span><span class="sxs-lookup"><span data-stu-id="ea567-105">Saved search display name.</span></span></param>
        <param name="query"><span data-ttu-id="ea567-106">保存された検索のクエリ式。</span><span class="sxs-lookup"><span data-stu-id="ea567-106">The query expression for the saved search.</span></span>
            <span data-ttu-id="ea567-107">参照用 https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-search-reference を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ea567-107">Please see https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-search-reference for reference.</span></span></param>
        <param name="version"><span data-ttu-id="ea567-108">クエリ言語のバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="ea567-108">The version number of the query lanuage.</span></span> <span data-ttu-id="ea567-109">ここでは、バージョン 1 のみを使用します。</span><span class="sxs-lookup"><span data-stu-id="ea567-109">Only verion 1 is allowed here.</span></span></param>
        <param name="id"><span data-ttu-id="ea567-110">保存された検索の id。</span><span class="sxs-lookup"><span data-stu-id="ea567-110">The id of the saved search.</span></span></param>
        <param name="etag"><span data-ttu-id="ea567-111">保存された検索の etag。</span><span class="sxs-lookup"><span data-stu-id="ea567-111">The etag of the saved search.</span></span></param>
        <param name="tags"><span data-ttu-id="ea567-112">保存された検索に関連付けられたタグ。</span><span class="sxs-lookup"><span data-stu-id="ea567-112">The tags attached to the saved search.</span></span></param>
        <summary>
            <span data-ttu-id="ea567-113">Savedsearch でクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea567-113">Initializes a new instance of the SavedSearch class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public string Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As String" />
      <MemberSignature Language="F#" Value="member this.Category : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.Category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea567-114">取得または保存された検索のカテゴリを設定します。</span><span class="sxs-lookup"><span data-stu-id="ea567-114">Gets or sets the category of the saved search.</span></span> <span data-ttu-id="ea567-115">これにより、保存済み検索を高速検索をユーザーにします。</span><span class="sxs-lookup"><span data-stu-id="ea567-115">This helps the user to find a saved search faster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.DisplayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea567-116">保存した検索条件を取得または設定の表示名。</span><span class="sxs-lookup"><span data-stu-id="ea567-116">Gets or sets saved search display name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
            <span data-ttu-id="ea567-117">取得または保存された検索の etag を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea567-117">Gets or sets the etag of the saved search.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
            <span data-ttu-id="ea567-118">保存された検索の id を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea567-118">Gets the id of the saved search.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public string Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As String" />
      <MemberSignature Language="F#" Value="member this.Query : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.Query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea567-119">取得または保存された検索のクエリ式を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea567-119">Gets or sets the query expression for the saved search.</span></span> <span data-ttu-id="ea567-120">参照用 https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-search-reference を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ea567-120">Please see https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-search-reference for reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IList(Of Tag)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.Tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.Tag&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea567-121">取得または保存された検索に関連付けられたタグを設定します。</span><span class="sxs-lookup"><span data-stu-id="ea567-121">Gets or sets the tags attached to the saved search.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="savedSearch.Validate " />
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
            <span data-ttu-id="ea567-122">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ea567-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ea567-123">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ea567-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public long Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Long" />
      <MemberSignature Language="F#" Value="member this.Version : int64 with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.Version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea567-124">取得またはクエリ言語のバージョン番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea567-124">Gets or sets the version number of the query lanuage.</span></span> <span data-ttu-id="ea567-125">ここでは、バージョン 1 のみを使用します。</span><span class="sxs-lookup"><span data-stu-id="ea567-125">Only verion 1 is allowed here.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>