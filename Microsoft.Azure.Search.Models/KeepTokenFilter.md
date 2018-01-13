<Type Name="KeepTokenFilter" FullName="Microsoft.Azure.Search.Models.KeepTokenFilter">
  <TypeSignature Language="C#" Value="public class KeepTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeepTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.KeepTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class KeepTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type KeepTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.KeepTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3ddf4-101">指定された単語の一覧に含まれるテキストのトークンのみが保持するトークン フィルターです。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-101">A token filter that only keeps tokens with text contained in a specified list of words.</span></span> <span data-ttu-id="3ddf4-102">このトークンのフィルターは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/KeepWordFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeepTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeepTokenFilter.#ctor" />
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
            <span data-ttu-id="3ddf4-103">KeepTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-103">Initializes a new instance of the KeepTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeepTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; keepWords, Nullable&lt;bool&gt; lowerCaseKeepWords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; keepWords, valuetype System.Nullable`1&lt;bool&gt; lowerCaseKeepWords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeepTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, keepWords As IList(Of String), Optional lowerCaseKeepWords As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.KeepTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.KeepTokenFilter" Usage="new Microsoft.Azure.Search.Models.KeepTokenFilter (name, keepWords, lowerCaseKeepWords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keepWords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="lowerCaseKeepWords" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3ddf4-104">トークンのフィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-104">The name of the token filter.</span></span> <span data-ttu-id="3ddf4-105">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="keepWords"><span data-ttu-id="3ddf4-106">保持するキーワードのリスト。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-106">The list of words to keep.</span></span></param>
        <param name="lowerCaseKeepWords"><span data-ttu-id="3ddf4-107">低くかどうかを示す値では、すべての単語をまず場合です。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-107">A value indicating whether to lower case all words first.</span></span> <span data-ttu-id="3ddf4-108">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-108">Default is false.</span></span></param>
        <summary>
            <span data-ttu-id="3ddf4-109">KeepTokenFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-109">Initializes a new instance of the KeepTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepWords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; KeepWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; KeepWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.KeepTokenFilter.KeepWords" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepWords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.KeepWords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.KeepTokenFilter.KeepWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keepWords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ddf4-110">取得または保持するキーワードのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-110">Gets or sets the list of words to keep.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LowerCaseKeepWords">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; LowerCaseKeepWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; LowerCaseKeepWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.KeepTokenFilter.LowerCaseKeepWords" />
      <MemberSignature Language="VB.NET" Value="Public Property LowerCaseKeepWords As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.LowerCaseKeepWords : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.KeepTokenFilter.LowerCaseKeepWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keepWordsCase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ddf4-111">取得または低いすべての単語をまずケースするかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-111">Gets or sets a value indicating whether to lower case all words first.</span></span> <span data-ttu-id="3ddf4-112">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-112">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeepTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="keepTokenFilter.Validate " />
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
            <span data-ttu-id="3ddf4-113">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3ddf4-114">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3ddf4-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>