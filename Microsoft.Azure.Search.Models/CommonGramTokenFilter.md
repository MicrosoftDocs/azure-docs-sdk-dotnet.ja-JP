<Type Name="CommonGramTokenFilter" FullName="Microsoft.Azure.Search.Models.CommonGramTokenFilter">
  <TypeSignature Language="C#" Value="public class CommonGramTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CommonGramTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.CommonGramTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class CommonGramTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type CommonGramTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.CommonGramTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            インデックス作成中に条件を頻繁に発生したため bigram を構築します。 1 つの用語のインデックス処理がすぎる、bigram オーバーレイにします。 このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/commongrams/CommonGramsFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CommonGramTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CommonGramTokenFilter.#ctor" />
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
            CommonGramTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CommonGramTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; commonWords, Nullable&lt;bool&gt; ignoreCase = null, Nullable&lt;bool&gt; useQueryMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; commonWords, valuetype System.Nullable`1&lt;bool&gt; ignoreCase, valuetype System.Nullable`1&lt;bool&gt; useQueryMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CommonGramTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, commonWords As IList(Of String), Optional ignoreCase As Nullable(Of Boolean) = null, Optional useQueryMode As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.CommonGramTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.CommonGramTokenFilter" Usage="new Microsoft.Azure.Search.Models.CommonGramTokenFilter (name, commonWords, ignoreCase, useQueryMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="commonWords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="ignoreCase" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="useQueryMode" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="commonWords">一般的な単語のセット。</param>
        <param name="ignoreCase">一致する一般的な単語が大文字小文字を区別するかどうかを示す値。 既定値は false です。</param>
        <param name="useQueryMode">トークンのフィルターがクエリ モードであるかどうかを示す値。 クエリ モードのときに、トークンのフィルターは bigram を生成し、し、一般的な単語と一般的な単語に続く 1 つの用語を削除します。 既定値は false です。</param>
        <summary>
            CommonGramTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonWords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CommonWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CommonWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CommonGramTokenFilter.CommonWords" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonWords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CommonWords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CommonGramTokenFilter.CommonWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commonWords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または一般的な単語のセットを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreCase">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreCase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreCase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CommonGramTokenFilter.IgnoreCase" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreCase As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreCase : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CommonGramTokenFilter.IgnoreCase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreCase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または一致する一般的な単語が大文字小文字を区別するかどうかを示す値を設定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseQueryMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseQueryMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseQueryMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CommonGramTokenFilter.UseQueryMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UseQueryMode As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseQueryMode : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CommonGramTokenFilter.UseQueryMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="queryMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークンのフィルターがクエリ モードであるかどうかを示す値を設定します。 クエリ モードのときに、トークンのフィルターは bigram を生成し、し、一般的な単語と一般的な単語に続く 1 つの用語を削除します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CommonGramTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="commonGramTokenFilter.Validate " />
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