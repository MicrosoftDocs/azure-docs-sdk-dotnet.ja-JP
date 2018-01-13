<Type Name="PatternReplaceTokenFilter" FullName="Microsoft.Azure.Search.Models.PatternReplaceTokenFilter">
  <TypeSignature Language="C#" Value="public class PatternReplaceTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PatternReplaceTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PatternReplaceTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type PatternReplaceTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PatternReplaceTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            入力文字列内の文字を置換する文字フィルターです。 使用して、正規表現を保持する文字シーケンスを識別する文字を識別する置換パターンを置き換えます。 パターンを入力文字列"aa bb aa bb"を指定するには、たとえば、"(aa)\s+(bb)"、および置換「$&amp;#1;$2」、結果は"aa #bb aa #bb"になります。 このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/pattern/PatternReplaceFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternReplaceTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.#ctor" />
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
            PatternReplaceTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternReplaceTokenFilter (string name, string pattern, string replacement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string pattern, string replacement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, pattern As String, replacement As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PatternReplaceTokenFilter : string * string * string -&gt; Microsoft.Azure.Search.Models.PatternReplaceTokenFilter" Usage="new Microsoft.Azure.Search.Models.PatternReplaceTokenFilter (name, pattern, replacement)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="pattern" Type="System.String" />
        <Parameter Name="replacement" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="pattern">正規表現パターン。</param>
        <param name="replacement">置換する文字列。</param>
        <summary>
            PatternReplaceTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pattern">
      <MemberSignature Language="C#" Value="public string Pattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Pattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.Pattern" />
      <MemberSignature Language="VB.NET" Value="Public Property Pattern As String" />
      <MemberSignature Language="F#" Value="member this.Pattern : string with get, set" Usage="Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.Pattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または正規表現パターンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replacement">
      <MemberSignature Language="C#" Value="public string Replacement { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Replacement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.Replacement" />
      <MemberSignature Language="VB.NET" Value="Public Property Replacement As String" />
      <MemberSignature Language="F#" Value="member this.Replacement : string with get, set" Usage="Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.Replacement" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replacement")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または置換するテキストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternReplaceTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="patternReplaceTokenFilter.Validate " />
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