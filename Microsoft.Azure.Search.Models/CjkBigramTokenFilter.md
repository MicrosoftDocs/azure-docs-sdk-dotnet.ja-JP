<Type Name="CjkBigramTokenFilter" FullName="Microsoft.Azure.Search.Models.CjkBigramTokenFilter">
  <TypeSignature Language="C#" Value="public class CjkBigramTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CjkBigramTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.CjkBigramTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class CjkBigramTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type CjkBigramTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.CjkBigramTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            StandardTokenizer から生成される CJK 用語の字を形成します。
            このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/cjk/CJKBigramFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CjkBigramTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.#ctor" />
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
            CjkBigramTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CjkBigramTokenFilter (string name, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; ignoreScripts = null, Nullable&lt;bool&gt; outputUnigrams = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; ignoreScripts, valuetype System.Nullable`1&lt;bool&gt; outputUnigrams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional ignoreScripts As IList(Of CjkBigramTokenFilterScripts) = null, Optional outputUnigrams As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.CjkBigramTokenFilter : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.CjkBigramTokenFilter" Usage="new Microsoft.Azure.Search.Models.CjkBigramTokenFilter (name, ignoreScripts, outputUnigrams)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ignoreScripts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt;" />
        <Parameter Name="outputUnigrams" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="ignoreScripts">無視するスクリプトです。</param>
        <param name="outputUnigrams">(False の場合)、単なる bigram または unigram および bigram (true の場合) の両方を出力するかどうかを示す値。
            既定値は false です。</param>
        <summary>
            CjkBigramTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreScripts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; IgnoreScripts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; IgnoreScripts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.IgnoreScripts" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreScripts As IList(Of CjkBigramTokenFilterScripts)" />
      <MemberSignature Language="F#" Value="member this.IgnoreScripts : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CjkBigramTokenFilter.IgnoreScripts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreScripts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を無視するスクリプト。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputUnigrams">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OutputUnigrams { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OutputUnigrams" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.OutputUnigrams" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputUnigrams As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OutputUnigrams : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CjkBigramTokenFilter.OutputUnigrams" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputUnigrams")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または (false の場合) に、単なる bigram または unigram および bigram (true の場合) の両方を出力するかどうかを示す値を設定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="cjkBigramTokenFilter.Validate " />
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>