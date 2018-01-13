<Type Name="StopAnalyzer" FullName="Microsoft.Azure.Search.Models.StopAnalyzer">
  <TypeSignature Language="C#" Value="public class StopAnalyzer : Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StopAnalyzer extends Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.StopAnalyzer" />
  <TypeSignature Language="VB.NET" Value="Public Class StopAnalyzer&#xA;Inherits Analyzer" />
  <TypeSignature Language="F#" Value="type StopAnalyzer = class&#xA;    inherit Analyzer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Analyzer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.StopAnalyzer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5c286-101">英字以外の場合; にあるテキストに分割します。ストップ ワードと小文字のトークンのフィルターを適用します。</span><span class="sxs-lookup"><span data-stu-id="5c286-101">Divides text at non-letters; Applies the lowercase and stopword token filters.</span></span> <span data-ttu-id="5c286-102">このアナライザーは、Apache Lucene を使用して実装されます。</span><span class="sxs-lookup"><span data-stu-id="5c286-102">This analyzer is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/StopAnalyzer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StopAnalyzer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopAnalyzer.#ctor" />
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
            <span data-ttu-id="5c286-103">StopAnalyzer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5c286-103">Initializes a new instance of the StopAnalyzer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StopAnalyzer (string name, System.Collections.Generic.IList&lt;string&gt; stopwords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; stopwords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopAnalyzer.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional stopwords As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.StopAnalyzer : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.StopAnalyzer" Usage="new Microsoft.Azure.Search.Models.StopAnalyzer (name, stopwords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="stopwords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5c286-104">アナライザーの名前です。</span><span class="sxs-lookup"><span data-stu-id="5c286-104">The name of the analyzer.</span></span> <span data-ttu-id="5c286-105">文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</span><span class="sxs-lookup"><span data-stu-id="5c286-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="stopwords"><span data-ttu-id="5c286-106">ストップ ワードの一覧。</span><span class="sxs-lookup"><span data-stu-id="5c286-106">A list of stopwords.</span></span></param>
        <summary>
            <span data-ttu-id="5c286-107">StopAnalyzer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5c286-107">Initializes a new instance of the StopAnalyzer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stopwords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Stopwords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Stopwords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopAnalyzer.Stopwords" />
      <MemberSignature Language="VB.NET" Value="Public Property Stopwords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Stopwords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopAnalyzer.Stopwords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stopwords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c286-108">取得または、ストップ ワードの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c286-108">Gets or sets a list of stopwords.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopAnalyzer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="stopAnalyzer.Validate " />
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
            <span data-ttu-id="5c286-109">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5c286-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5c286-110">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5c286-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>