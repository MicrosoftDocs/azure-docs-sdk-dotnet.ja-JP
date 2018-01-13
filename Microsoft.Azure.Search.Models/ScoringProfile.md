<Type Name="ScoringProfile" FullName="Microsoft.Azure.Search.Models.ScoringProfile">
  <TypeSignature Language="C#" Value="public class ScoringProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScoringProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.ScoringProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ScoringProfile" />
  <TypeSignature Language="F#" Value="type ScoringProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="58be6-101">Azure Search インデックスの検索クエリでスコア付けに影響を与えるパラメーターを定義します。</span><span class="sxs-lookup"><span data-stu-id="58be6-101">Defines parameters for an Azure Search index that influence scoring in search queries.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Add-scoring-profiles-to-a-search-index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScoringProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringProfile.#ctor" />
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
            <span data-ttu-id="58be6-102">ScoringProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="58be6-102">Initializes a new instance of the ScoringProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScoringProfile (string name, Microsoft.Azure.Search.Models.TextWeights textWeights = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt; functions = null, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; functionAggregation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.TextWeights textWeights, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.ScoringFunction&gt; functions, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; functionAggregation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringProfile.#ctor(System.String,Microsoft.Azure.Search.Models.TextWeights,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.ScoringFunction},System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionAggregation})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.ScoringProfile : string * Microsoft.Azure.Search.Models.TextWeights * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt; * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; -&gt; Microsoft.Azure.Search.Models.ScoringProfile" Usage="new Microsoft.Azure.Search.Models.ScoringProfile (name, textWeights, functions, functionAggregation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="textWeights" Type="Microsoft.Azure.Search.Models.TextWeights" />
        <Parameter Name="functions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt;" />
        <Parameter Name="functionAggregation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="58be6-103">スコア付けプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="58be6-103">The name of the scoring profile.</span></span></param>
        <param name="textWeights"><span data-ttu-id="58be6-104">スコアを向上させるためのパラメーターは、特定のインデックス フィールドのテキストの一致に基づいています。</span><span class="sxs-lookup"><span data-stu-id="58be6-104">Parameters that boost scoring based on text matches in certain index fields.</span></span></param>
        <param name="functions"><span data-ttu-id="58be6-105">ドキュメントのスコア付けに影響を与える関数のコレクション。</span><span class="sxs-lookup"><span data-stu-id="58be6-105">The collection of functions that influence the scoring of documents.</span></span></param>
        <param name="functionAggregation"><span data-ttu-id="58be6-106">個々 のスコア付け関数の結果を結合する方法を示す値。</span><span class="sxs-lookup"><span data-stu-id="58be6-106">A value indicating how the results of individual scoring functions should be combined.</span></span>
            <span data-ttu-id="58be6-107">既定値は「合計」です。</span><span class="sxs-lookup"><span data-stu-id="58be6-107">Defaults to "Sum".</span></span> <span data-ttu-id="58be6-108">スコア付け関数が存在しない場合、無視されます。</span><span class="sxs-lookup"><span data-stu-id="58be6-108">Ignored if there are no scoring functions.</span></span>
            <span data-ttu-id="58be6-109">使用可能な値が含まれます: 'sum'、'平均'、'最小'、'最大'、'firstMatching'</span><span class="sxs-lookup"><span data-stu-id="58be6-109">Possible values include: 'sum', 'average', 'minimum', 'maximum', 'firstMatching'</span></span></param>
        <summary>
            <span data-ttu-id="58be6-110">ScoringProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="58be6-110">Initializes a new instance of the ScoringProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FunctionAggregation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; FunctionAggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; FunctionAggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringProfile.FunctionAggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property FunctionAggregation As Nullable(Of ScoringFunctionAggregation)" />
      <MemberSignature Language="F#" Value="member this.FunctionAggregation : Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; with get, set" Usage="Microsoft.Azure.Search.Models.ScoringProfile.FunctionAggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="functionAggregation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="58be6-111">取得または個々 のスコア付け関数の結果を結合する方法を示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="58be6-111">Gets or sets a value indicating how the results of individual scoring functions should be combined.</span></span> <span data-ttu-id="58be6-112">既定値は「合計」です。</span><span class="sxs-lookup"><span data-stu-id="58be6-112">Defaults to "Sum".</span></span> <span data-ttu-id="58be6-113">スコア付け関数が存在しない場合、無視されます。</span><span class="sxs-lookup"><span data-stu-id="58be6-113">Ignored if there are no scoring functions.</span></span> <span data-ttu-id="58be6-114">使用可能な値が含まれます: 'sum'、'平均'、'最小'、'最大'、'firstMatching'</span><span class="sxs-lookup"><span data-stu-id="58be6-114">Possible values include: 'sum', 'average', 'minimum', 'maximum', 'firstMatching'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Functions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt; Functions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.ScoringFunction&gt; Functions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringProfile.Functions" />
      <MemberSignature Language="VB.NET" Value="Public Property Functions As IList(Of ScoringFunction)" />
      <MemberSignature Language="F#" Value="member this.Functions : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt; with get, set" Usage="Microsoft.Azure.Search.Models.ScoringProfile.Functions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="functions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="58be6-115">取得またはドキュメントのスコア付けに影響を与える関数のコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="58be6-115">Gets or sets the collection of functions that influence the scoring of documents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringProfile.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.ScoringProfile.Name" />
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
            <span data-ttu-id="58be6-116">取得またはスコア付けプロファイルの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="58be6-116">Gets or sets the name of the scoring profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TextWeights">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.TextWeights TextWeights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.TextWeights TextWeights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringProfile.TextWeights" />
      <MemberSignature Language="VB.NET" Value="Public Property TextWeights As TextWeights" />
      <MemberSignature Language="F#" Value="member this.TextWeights : Microsoft.Azure.Search.Models.TextWeights with get, set" Usage="Microsoft.Azure.Search.Models.ScoringProfile.TextWeights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="text")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TextWeights</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="58be6-117">取得またはその boost スコアリング特定のインデックス フィールドのテキストとの一致に基づいてパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="58be6-117">Gets or sets parameters that boost scoring based on text matches in certain index fields.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scoringProfile.Validate " />
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
            <span data-ttu-id="58be6-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="58be6-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="58be6-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="58be6-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>