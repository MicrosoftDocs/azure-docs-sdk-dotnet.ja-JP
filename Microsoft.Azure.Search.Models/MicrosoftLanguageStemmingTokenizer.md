<Type Name="MicrosoftLanguageStemmingTokenizer" FullName="Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer">
  <TypeSignature Language="C#" Value="public class MicrosoftLanguageStemmingTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MicrosoftLanguageStemmingTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class MicrosoftLanguageStemmingTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type MicrosoftLanguageStemmingTokenizer = class&#xA;    inherit Tokenizer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Tokenizer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.MicrosoftLanguageStemmingTokenizer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            言語固有の規則を使用してテキストを分割し、基本フォームに単語を短縮します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MicrosoftLanguageStemmingTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.#ctor" />
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
            MicrosoftLanguageStemmingTokenizer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MicrosoftLanguageStemmingTokenizer (string name, Nullable&lt;int&gt; maxTokenLength = null, Nullable&lt;bool&gt; isSearchTokenizer = null, Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; language = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; maxTokenLength, valuetype System.Nullable`1&lt;bool&gt; isSearchTokenizer, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; language) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional maxTokenLength As Nullable(Of Integer) = null, Optional isSearchTokenizer As Nullable(Of Boolean) = null, Optional language As Nullable(Of MicrosoftStemmingTokenizerLanguage) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; -&gt; Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer" Usage="new Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer (name, maxTokenLength, isSearchTokenizer, language)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxTokenLength" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isSearchTokenizer" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="language" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt;" />
      </Parameters>
      <Docs>
        <param name="name">トークナイザの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="maxTokenLength">トークンの最大長。 トークンの最大長を超えては分割されます。 使用できる最大トークン長は、300 文字です。 300 文字はまず 300 の長さのトークンに分割し、これらのトークンの各分割しより長いトークンは、最大トークン長文字セットに基づいています。 既定値は
            255.</param>
        <param name="isSearchTokenizer">トークナイザの使用方法を示す値です。 インデックス作成のトークナイザとして使用する場合は false に設定、検索トークナイザとして使用する場合、true に設定します。 既定値は false です。</param>
        <param name="language">使用する言語です。 既定値は英語です。
            使用可能な値が含まれます: 'アラビア'、'バングラ語'、'ブルガリア語'、'カタロニア'、'クロアチア語'、'チェコ語'、'デンマーク'、'オランダ'、'english'、'エストニア語'、'フィンランド'、'フランス語の'、'ドイツ語'、'ギリシャ語'、'グジャラート語'、'ヘブライ語'、'ヒンディー語'、'ハンガリー語'、'アイスランド語'、'インドネシア語'、'イタリア語 '、'カンナダ語'、'ラトビア語'、'リトアニア語'、'マレー'、'マラヤーラム語'、'マラーティー語'、'norwegianBokmaal'、'ポーランド語'、'ポルトガル語-'、'portugueseBrazilian'、'パンジャブ'、'ルーマニア語'、'ロシア語'、'serbianCyrillic'、'serbianLatin'、'スロバキア語'、'slovenian'、'スペイン語 '、'スウェーデン'、'タミール'、'テルグ'、'トルコ語'、'ウクライナ語'、'ウルドゥ'</param>
        <summary>
            MicrosoftLanguageStemmingTokenizer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSearchTokenizer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSearchTokenizer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSearchTokenizer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.IsSearchTokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSearchTokenizer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSearchTokenizer : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.IsSearchTokenizer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isSearchTokenizer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークナイザの使用方法を示す値を設定します。 インデックス作成のトークナイザとして使用する場合は false に設定、検索トークナイザとして使用する場合、true に設定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Language">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; Language { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; Language" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.Language" />
      <MemberSignature Language="VB.NET" Value="Public Property Language As Nullable(Of MicrosoftStemmingTokenizerLanguage)" />
      <MemberSignature Language="F#" Value="member this.Language : Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.Language" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="language")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftStemmingTokenizerLanguage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用する言語を設定します。 既定値は英語です。 使用可能な値が含まれます: 'アラビア'、'バングラ語'、'ブルガリア語'、'カタロニア'、'クロアチア語'、'チェコ語'、'デンマーク'、'オランダ'、'english'、'エストニア語'、'フィンランド'、'フランス語の'、'ドイツ語'、'ギリシャ語'、'グジャラート語'、'ヘブライ語'、'ヒンディー語'、'ハンガリー語'、'アイスランド語'、'インドネシア語'、'イタリア語 '、'カンナダ語'、'ラトビア語'、'リトアニア語'、'マレー'、'マラヤーラム語'、'マラーティー語'、'norwegianBokmaal'、'ポーランド語'、'ポルトガル語-'、'portugueseBrazilian'、'パンジャブ'、'ルーマニア語'、'ロシア語'、'serbianCyrillic'、'serbianLatin'、'スロバキア語'、'slovenian'、'スペイン語 '、'スウェーデン'、'タミール'、'テルグ'、'トルコ語'、'ウクライナ語'、'ウルドゥ'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.MaxTokenLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenLength As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenLength : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.MaxTokenLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTokenLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または最大トークン長を設定します。 トークンの最大長を超えては分割されます。 使用できる最大トークン長は、300 文字です。 300 文字はまず 300 の長さのトークンに分割し、これらのトークンの各分割しより長いトークンは、最大トークン長文字セットに基づいています。 既定値は 255 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageStemmingTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="microsoftLanguageStemmingTokenizer.Validate " />
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