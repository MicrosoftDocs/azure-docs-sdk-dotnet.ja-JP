<Type Name="EdgeNGramTokenFilter" FullName="Microsoft.Azure.Search.Models.EdgeNGramTokenFilter">
  <TypeSignature Language="C#" Value="public class EdgeNGramTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EdgeNGramTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.EdgeNGramTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class EdgeNGramTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type EdgeNGramTokenFilter = class&#xA;    inherit TokenFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.TokenFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.EdgeNGramTokenFilter")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Obsolete("This type is obsolete. Please use EdgeNGramTokenFilterV2 instead.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4c188-101">N-gram の前面または入力トークンの背面から指定されたサイズが生成されます。</span><span class="sxs-lookup"><span data-stu-id="4c188-101">Generates n-grams of the given size(s) starting from the front or the back of an input token.</span></span> <span data-ttu-id="4c188-102">このトークンのフィルターは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="4c188-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/EdgeNGramTokenFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EdgeNGramTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.EdgeNGramTokenFilter.#ctor" />
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
            <span data-ttu-id="4c188-103">EdgeNGramTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4c188-103">Initializes a new instance of the EdgeNGramTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EdgeNGramTokenFilter (string name, Nullable&lt;int&gt; minGram = null, Nullable&lt;int&gt; maxGram = null, Nullable&lt;Microsoft.Azure.Search.Models.EdgeNGramTokenFilterSide&gt; side = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; minGram, valuetype System.Nullable`1&lt;int32&gt; maxGram, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.EdgeNGramTokenFilterSide&gt; side) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.EdgeNGramTokenFilter.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Search.Models.EdgeNGramTokenFilterSide})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional minGram As Nullable(Of Integer) = null, Optional maxGram As Nullable(Of Integer) = null, Optional side As Nullable(Of EdgeNGramTokenFilterSide) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.EdgeNGramTokenFilter : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Search.Models.EdgeNGramTokenFilterSide&gt; -&gt; Microsoft.Azure.Search.Models.EdgeNGramTokenFilter" Usage="new Microsoft.Azure.Search.Models.EdgeNGramTokenFilter (name, minGram, maxGram, side)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="minGram" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxGram" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="side" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.EdgeNGramTokenFilterSide&gt;" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="minGram">To be added.</param>
        <param name="maxGram">To be added.</param>
        <param name="side">To be added.</param>
        <summary>
            <span data-ttu-id="4c188-104">EdgeNGramTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4c188-104">Initializes a new instance of the EdgeNGramTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.EdgeNGramTokenFilter.MaxGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.EdgeNGramTokenFilter.MaxGram" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxGram")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c188-105">取得または n グラムの最大の長さを設定します。</span><span class="sxs-lookup"><span data-stu-id="4c188-105">Gets or sets the maximum n-gram length.</span></span> <span data-ttu-id="4c188-106">既定値は 2 です。</span><span class="sxs-lookup"><span data-stu-id="4c188-106">Default is 2.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.EdgeNGramTokenFilter.MinGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MinGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.EdgeNGramTokenFilter.MinGram" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minGram")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c188-107">取得または n グラムの最小の長さを設定します。</span><span class="sxs-lookup"><span data-stu-id="4c188-107">Gets or sets the minimum n-gram length.</span></span> <span data-ttu-id="4c188-108">既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="4c188-108">Default is 1.</span></span> <span data-ttu-id="4c188-109">MaxGram の値よりも小さい必要があります。</span><span class="sxs-lookup"><span data-stu-id="4c188-109">Must be less than the value of maxGram.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Side">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.EdgeNGramTokenFilterSide&gt; Side { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.EdgeNGramTokenFilterSide&gt; Side" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.EdgeNGramTokenFilter.Side" />
      <MemberSignature Language="VB.NET" Value="Public Property Side As Nullable(Of EdgeNGramTokenFilterSide)" />
      <MemberSignature Language="F#" Value="member this.Side : Nullable&lt;Microsoft.Azure.Search.Models.EdgeNGramTokenFilterSide&gt; with get, set" Usage="Microsoft.Azure.Search.Models.EdgeNGramTokenFilter.Side" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="side")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.EdgeNGramTokenFilterSide&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4c188-110">取得または設定は、入力のどちら側 n グラムはから生成するかを指定します。</span><span class="sxs-lookup"><span data-stu-id="4c188-110">Gets or sets specifies which side of the input the n-gram should be generated from.</span></span> <span data-ttu-id="4c188-111">既定値は"front"です。</span><span class="sxs-lookup"><span data-stu-id="4c188-111">Default is "front".</span></span> <span data-ttu-id="4c188-112">使用可能な値が含まれます: 'フロント'、'back'</span><span class="sxs-lookup"><span data-stu-id="4c188-112">Possible values include: 'front', 'back'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.EdgeNGramTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="edgeNGramTokenFilter.Validate " />
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
            <span data-ttu-id="4c188-113">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4c188-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4c188-114">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4c188-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>