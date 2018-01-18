<Type Name="Index" FullName="Microsoft.Azure.Search.Models.Index">
  <TypeSignature Language="C#" Value="public class Index : Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Index extends System.Object implements class Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.Index" />
  <TypeSignature Language="VB.NET" Value="Public Class Index&#xA;Implements IResourceWithETag" />
  <TypeSignature Language="F#" Value="type Index = class&#xA;    interface IResourceWithETag" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Search.Models.IResourceWithETag</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="78718-101">フィールドとインデックスの検索動作について説明する Azure Search のインデックスの定義を表します。</span><span class="sxs-lookup"><span data-stu-id="78718-101">Represents an index definition in Azure Search, which describes the fields and search behavior of an index.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Index ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Index.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="78718-102">Index クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="78718-102">Initializes a new instance of the Index class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Index (string name, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt; fields, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringProfile&gt; scoringProfiles = null, string defaultScoringProfile = null, Microsoft.Azure.Search.Models.CorsOptions corsOptions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Suggester&gt; suggesters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Analyzer&gt; analyzers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Tokenizer&gt; tokenizers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilter&gt; tokenFilters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilter&gt; charFilters = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Field&gt; fields, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.ScoringProfile&gt; scoringProfiles, string defaultScoringProfile, class Microsoft.Azure.Search.Models.CorsOptions corsOptions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Suggester&gt; suggesters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Analyzer&gt; analyzers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Tokenizer&gt; tokenizers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilter&gt; tokenFilters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilter&gt; charFilters, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Index.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.Field},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.ScoringProfile},System.String,Microsoft.Azure.Search.Models.CorsOptions,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.Suggester},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.Analyzer},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.Tokenizer},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.TokenFilter},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.CharFilter},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Index : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringProfile&gt; * string * Microsoft.Azure.Search.Models.CorsOptions * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Suggester&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Analyzer&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Tokenizer&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilter&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilter&gt; * string -&gt; Microsoft.Azure.Search.Models.Index" Usage="new Microsoft.Azure.Search.Models.Index (name, fields, scoringProfiles, defaultScoringProfile, corsOptions, suggesters, analyzers, tokenizers, tokenFilters, charFilters, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="fields" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt;" />
        <Parameter Name="scoringProfiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringProfile&gt;" />
        <Parameter Name="defaultScoringProfile" Type="System.String" />
        <Parameter Name="corsOptions" Type="Microsoft.Azure.Search.Models.CorsOptions" />
        <Parameter Name="suggesters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Suggester&gt;" />
        <Parameter Name="analyzers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Analyzer&gt;" />
        <Parameter Name="tokenizers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Tokenizer&gt;" />
        <Parameter Name="tokenFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilter&gt;" />
        <Parameter Name="charFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilter&gt;" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="78718-103">インデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="78718-103">The name of the index.</span></span></param>
        <param name="fields"><span data-ttu-id="78718-104">インデックスのフィールドです。</span><span class="sxs-lookup"><span data-stu-id="78718-104">The fields of the index.</span></span></param>
        <param name="scoringProfiles"><span data-ttu-id="78718-105">インデックスのスコア付けプロファイル。</span><span class="sxs-lookup"><span data-stu-id="78718-105">The scoring profiles for the index.</span></span></param>
        <param name="defaultScoringProfile"><span data-ttu-id="78718-106">クエリで指定されていない場合に使用するスコア付けプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="78718-106">The name of the scoring profile to use if none is specified in the query.</span></span> <span data-ttu-id="78718-107">このプロパティを設定しないと、クエリのスコア付けプロファイルが指定されていない、し、既定のスコア付け (tf idf) が使用されます。</span><span class="sxs-lookup"><span data-stu-id="78718-107">If this property is not set and no scoring profile is specified in the query, then default scoring (tf-idf) will be used.</span></span></param>
        <param name="corsOptions"><span data-ttu-id="78718-108">インデックスのクロス オリジン リソース共有 (CORS) を制御するオプション。</span><span class="sxs-lookup"><span data-stu-id="78718-108">Options to control Cross-Origin Resource Sharing (CORS) for the index.</span></span></param>
        <param name="suggesters"><span data-ttu-id="78718-109">インデックスの suggesters します。</span><span class="sxs-lookup"><span data-stu-id="78718-109">The suggesters for the index.</span></span></param>
        <param name="analyzers"><span data-ttu-id="78718-110">インデックスのアナライザーです。</span><span class="sxs-lookup"><span data-stu-id="78718-110">The analyzers for the index.</span></span></param>
        <param name="tokenizers"><span data-ttu-id="78718-111">インデックスのサロゲートです。</span><span class="sxs-lookup"><span data-stu-id="78718-111">The tokenizers for the index.</span></span></param>
        <param name="tokenFilters"><span data-ttu-id="78718-112">インデックスのトークンのフィルター。</span><span class="sxs-lookup"><span data-stu-id="78718-112">The token filters for the index.</span></span></param>
        <param name="charFilters"><span data-ttu-id="78718-113">インデックスの文字フィルター。</span><span class="sxs-lookup"><span data-stu-id="78718-113">The character filters for the index.</span></span></param>
        <param name="eTag"><span data-ttu-id="78718-114">インデックスの ETag。</span><span class="sxs-lookup"><span data-stu-id="78718-114">The ETag of the index.</span></span></param>
        <summary>
            <span data-ttu-id="78718-115">Index クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="78718-115">Initializes a new instance of the Index class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Analyzers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Analyzer&gt; Analyzers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Analyzer&gt; Analyzers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.Analyzers" />
      <MemberSignature Language="VB.NET" Value="Public Property Analyzers As IList(Of Analyzer)" />
      <MemberSignature Language="F#" Value="member this.Analyzers : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Analyzer&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Index.Analyzers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="analyzers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Analyzer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78718-116">取得またはインデックスのアナライザーを設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-116">Gets or sets the analyzers for the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CharFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilter&gt; CharFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilter&gt; CharFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.CharFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property CharFilters As IList(Of CharFilter)" />
      <MemberSignature Language="F#" Value="member this.CharFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilter&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Index.CharFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="charFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78718-117">取得またはインデックスの文字のフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-117">Gets or sets the character filters for the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorsOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.CorsOptions CorsOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.CorsOptions CorsOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.CorsOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property CorsOptions As CorsOptions" />
      <MemberSignature Language="F#" Value="member this.CorsOptions : Microsoft.Azure.Search.Models.CorsOptions with get, set" Usage="Microsoft.Azure.Search.Models.Index.CorsOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="corsOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.CorsOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78718-118">取得またはインデックスのクロス オリジン リソース共有 (CORS) を制御するオプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-118">Gets or sets options to control Cross-Origin Resource Sharing (CORS) for the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultScoringProfile">
      <MemberSignature Language="C#" Value="public string DefaultScoringProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultScoringProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.DefaultScoringProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultScoringProfile As String" />
      <MemberSignature Language="F#" Value="member this.DefaultScoringProfile : string with get, set" Usage="Microsoft.Azure.Search.Models.Index.DefaultScoringProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultScoringProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78718-119">取得またはクエリで指定されていない場合に使用するスコア付けプロファイルの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-119">Gets or sets the name of the scoring profile to use if none is specified in the query.</span></span> <span data-ttu-id="78718-120">このプロパティを設定しないと、クエリのスコア付けプロファイルが指定されていない、し、既定のスコア付け (tf idf) が使用されます。</span><span class="sxs-lookup"><span data-stu-id="78718-120">If this property is not set and no scoring profile is specified in the query, then default scoring (tf-idf) will be used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Search.Models.Index.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="@odata.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78718-121">取得またはインデックスの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-121">Gets or sets the ETag of the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fields">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt; Fields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Field&gt; Fields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.Fields" />
      <MemberSignature Language="VB.NET" Value="Public Property Fields As IList(Of Field)" />
      <MemberSignature Language="F#" Value="member this.Fields : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Index.Fields" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fields")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78718-122">取得またはインデックスのフィールドを設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-122">Gets or sets the fields of the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.Index.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="78718-123">取得またはインデックスの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-123">Gets or sets the name of the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScoringProfiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringProfile&gt; ScoringProfiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.ScoringProfile&gt; ScoringProfiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.ScoringProfiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ScoringProfiles As IList(Of ScoringProfile)" />
      <MemberSignature Language="F#" Value="member this.ScoringProfiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringProfile&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Index.ScoringProfiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scoringProfiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringProfile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78718-124">取得またはインデックスのスコア付けプロファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-124">Gets or sets the scoring profiles for the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suggesters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Suggester&gt; Suggesters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Suggester&gt; Suggesters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.Suggesters" />
      <MemberSignature Language="VB.NET" Value="Public Property Suggesters As IList(Of Suggester)" />
      <MemberSignature Language="F#" Value="member this.Suggesters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Suggester&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Index.Suggesters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="suggesters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Suggester&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78718-125">取得またはインデックスの suggesters を設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-125">Gets or sets the suggesters for the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilter&gt; TokenFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilter&gt; TokenFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.TokenFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenFilters As IList(Of TokenFilter)" />
      <MemberSignature Language="F#" Value="member this.TokenFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilter&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Index.TokenFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78718-126">取得またはインデックスのトークンのフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-126">Gets or sets the token filters for the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tokenizers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Tokenizer&gt; Tokenizers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Tokenizer&gt; Tokenizers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Index.Tokenizers" />
      <MemberSignature Language="VB.NET" Value="Public Property Tokenizers As IList(Of Tokenizer)" />
      <MemberSignature Language="F#" Value="member this.Tokenizers : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Tokenizer&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Index.Tokenizers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenizers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Tokenizer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78718-127">取得またはインデックスのサロゲートを設定します。</span><span class="sxs-lookup"><span data-stu-id="78718-127">Gets or sets the tokenizers for the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Index.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="index.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="78718-128">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="78718-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="78718-129">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="78718-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>