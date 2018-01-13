<Type Name="StopwordsTokenFilter" FullName="Microsoft.Azure.Search.Models.StopwordsTokenFilter">
  <TypeSignature Language="C#" Value="public class StopwordsTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StopwordsTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.StopwordsTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class StopwordsTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type StopwordsTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.StopwordsTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            削除は、トークンのストリームから単語を停止します。 このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/StopFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StopwordsTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopwordsTokenFilter.#ctor" />
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
            StopwordsTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StopwordsTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; stopwords = null, Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; stopwordsList = null, Nullable&lt;bool&gt; ignoreCase = null, Nullable&lt;bool&gt; removeTrailingStopWords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; stopwords, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.StopwordsList&gt; stopwordsList, valuetype System.Nullable`1&lt;bool&gt; ignoreCase, valuetype System.Nullable`1&lt;bool&gt; removeTrailingStopWords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopwordsTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Search.Models.StopwordsList},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional stopwords As IList(Of String) = null, Optional stopwordsList As Nullable(Of StopwordsList) = null, Optional ignoreCase As Nullable(Of Boolean) = null, Optional removeTrailingStopWords As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.StopwordsTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.StopwordsTokenFilter" Usage="new Microsoft.Azure.Search.Models.StopwordsTokenFilter (name, stopwords, stopwordsList, ignoreCase, removeTrailingStopWords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="stopwords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="stopwordsList" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt;" />
        <Parameter Name="ignoreCase" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="removeTrailingStopWords" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="stopwords">ストップ ワードの一覧です。 このプロパティは、ストップ ワードの一覧は両方とも設定できません。</param>
        <param name="stopwordsList">使用するストップ ワードの定義済みの一覧です。
            このプロパティは、ストップ ワードは両方とも設定できません。
            既定では英語です。 使用可能な値が含まれます: 'アラビア'、'アルメニア'、'バスク語'、'(ブラジル)'、'ブルガリア語'、'カタロニア'、'チェコ語'、'デンマーク'、'オランダ'、'english'、'フィンランド'、'フランス語の'、'ガリシア'、'ドイツ語'、'ギリシャ'、'ヒンディー語'、'ハンガリー語'、'インドネシア語'、'アイルランド語'、'イタリア語'、'ラトビア語 '、'ノルウェー語'、'ペルシャ'、'ポルトガル語-'、'ルーマニア語'、'ロシア語'、'sorani'、'スペイン'、'スウェーデン'、'タイ'、'トルコ語'</param>
        <param name="ignoreCase">大文字小文字を区別するかどうかを示す値。
            True の場合、すべての単語は最初に小文字に変換されます。 既定値は false です。</param>
        <param name="removeTrailingStopWords">ストップ ワードである場合は、最後の検索用語を無視するかどうかを示す値。 既定値は true です。</param>
        <summary>
            StopwordsTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreCase">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreCase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreCase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.IgnoreCase" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreCase As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreCase : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.IgnoreCase" />
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
            取得または大文字小文字を区別するかどうかを示す値を設定します。 True の場合、すべての単語は最初に小文字に変換されます。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveTrailingStopWords">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RemoveTrailingStopWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RemoveTrailingStopWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.RemoveTrailingStopWords" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveTrailingStopWords As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveTrailingStopWords : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.RemoveTrailingStopWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="removeTrailing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、ストップ ワードである場合は、最後の検索用語を無視するかどうかを示す値を設定します。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stopwords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Stopwords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Stopwords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.Stopwords" />
      <MemberSignature Language="VB.NET" Value="Public Property Stopwords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Stopwords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.Stopwords" />
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
            取得または、ストップ ワードの一覧を設定します。 このプロパティは、ストップ ワードの一覧は両方とも設定できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopwordsList">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; StopwordsList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.StopwordsList&gt; StopwordsList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.StopwordsList" />
      <MemberSignature Language="VB.NET" Value="Public Property StopwordsList As Nullable(Of StopwordsList)" />
      <MemberSignature Language="F#" Value="member this.StopwordsList : Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.StopwordsList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stopwordsList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用するストップ ワードの定義済みの一覧を設定します。 このプロパティは、ストップ ワードは両方とも設定できません。 既定では英語です。
            使用可能な値が含まれます: 'アラビア'、'アルメニア'、'バスク語'、'(ブラジル)'、'ブルガリア語'、'カタロニア'、'チェコ語'、'デンマーク'、'オランダ'、'english'、'フィンランド'、'フランス語の'、'ガリシア'、'ドイツ語'、'ギリシャ'、'ヒンディー語'、'ハンガリー語'、'インドネシア語'、'アイルランド語'、'イタリア語'、'ラトビア語 '、'ノルウェー語'、'ペルシャ'、'ポルトガル語-'、'ルーマニア語'、'ロシア語'、'sorani'、'スペイン'、'スウェーデン'、'タイ'、'トルコ語'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopwordsTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="stopwordsTokenFilter.Validate " />
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