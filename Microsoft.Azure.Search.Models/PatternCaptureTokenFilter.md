<Type Name="PatternCaptureTokenFilter" FullName="Microsoft.Azure.Search.Models.PatternCaptureTokenFilter">
  <TypeSignature Language="C#" Value="public class PatternCaptureTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PatternCaptureTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PatternCaptureTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type PatternCaptureTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PatternCaptureTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Java regex を使用して、1 つまたは複数のパターンのキャプチャ グループごとに 1 つの複数のトークンを生成します。 このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/pattern/PatternCaptureGroupTokenFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternCaptureTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.#ctor" />
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
            PatternCaptureTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternCaptureTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; patterns, Nullable&lt;bool&gt; preserveOriginal = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; patterns, valuetype System.Nullable`1&lt;bool&gt; preserveOriginal) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, patterns As IList(Of String), Optional preserveOriginal As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PatternCaptureTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.PatternCaptureTokenFilter" Usage="new Microsoft.Azure.Search.Models.PatternCaptureTokenFilter (name, patterns, preserveOriginal)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="patterns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="preserveOriginal" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="patterns">各トークンと照合するパターンの一覧。</param>
        <param name="preserveOriginal">いずれのパターンと一致する場合でも、元のトークンを返すかどうかを示す値。 既定値は true です。</param>
        <summary>
            PatternCaptureTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patterns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Patterns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Patterns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.Patterns" />
      <MemberSignature Language="VB.NET" Value="Public Property Patterns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Patterns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.Patterns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="patterns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または各トークンと照合するパターンのリストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreserveOriginal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PreserveOriginal { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PreserveOriginal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.PreserveOriginal" />
      <MemberSignature Language="VB.NET" Value="Public Property PreserveOriginal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PreserveOriginal : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.PreserveOriginal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preserveOriginal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパターンのいずれかと一致する場合でも、元のトークンを返すかどうかを示す値を設定します。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="patternCaptureTokenFilter.Validate " />
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