<Type Name="StemmerOverrideTokenFilter" FullName="Microsoft.Azure.Search.Models.StemmerOverrideTokenFilter">
  <TypeSignature Language="C#" Value="public class StemmerOverrideTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StemmerOverrideTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.StemmerOverrideTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class StemmerOverrideTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type StemmerOverrideTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.StemmerOverrideTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="37ee0-101">その他のステミングを上書きする機能をカスタム辞書ベースのステミングをフィルター処理を提供します。</span><span class="sxs-lookup"><span data-stu-id="37ee0-101">Provides the ability to override other stemming filters with custom dictionary-based stemming.</span></span> <span data-ttu-id="37ee0-102">ディクショナリ語幹用語は、チェーン内にステミング機能の語幹するがないように、キーワードとしてマークされます。</span><span class="sxs-lookup"><span data-stu-id="37ee0-102">Any dictionary-stemmed terms will be marked as keywords so that they will not be stemmed with stemmers down the chain.</span></span> <span data-ttu-id="37ee0-103">語幹検索、フィルターの前に配置する必要があります。</span><span class="sxs-lookup"><span data-stu-id="37ee0-103">Must be placed before any stemming filters.</span></span> <span data-ttu-id="37ee0-104">このトークンのフィルターは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="37ee0-104">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/StemmerOverrideFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StemmerOverrideTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StemmerOverrideTokenFilter.#ctor" />
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
            <span data-ttu-id="37ee0-105">StemmerOverrideTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="37ee0-105">Initializes a new instance of the StemmerOverrideTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StemmerOverrideTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; rules);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; rules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StemmerOverrideTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, rules As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.StemmerOverrideTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.StemmerOverrideTokenFilter" Usage="new Microsoft.Azure.Search.Models.StemmerOverrideTokenFilter (name, rules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="rules" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="37ee0-106">トークンのフィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="37ee0-106">The name of the token filter.</span></span> <span data-ttu-id="37ee0-107">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="37ee0-107">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="rules"><span data-ttu-id="37ee0-108">語幹次の形式でルールの一覧:"word =&gt;ステム"、たとえば:"実行 =&gt;実行"です。</span><span class="sxs-lookup"><span data-stu-id="37ee0-108">A list of stemming rules in the following format: "word =&gt; stem", for example: "ran =&gt; run".</span></span></param>
        <summary>
            <span data-ttu-id="37ee0-109">StemmerOverrideTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="37ee0-109">Initializes a new instance of the StemmerOverrideTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Rules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Rules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StemmerOverrideTokenFilter.Rules" />
      <MemberSignature Language="VB.NET" Value="Public Property Rules As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Rules : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StemmerOverrideTokenFilter.Rules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="37ee0-110">次の形式でルールを語形変化の一覧の設定を取得または:"word =&amp;gt;ステム"、たとえば:"実行 =&amp;gt;"を実行します。</span><span class="sxs-lookup"><span data-stu-id="37ee0-110">Gets or sets a list of stemming rules in the following format: "word =&amp;gt; stem", for example: "ran =&amp;gt; run".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StemmerOverrideTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="stemmerOverrideTokenFilter.Validate " />
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
            <span data-ttu-id="37ee0-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="37ee0-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="37ee0-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="37ee0-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>