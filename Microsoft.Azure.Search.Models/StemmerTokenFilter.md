<Type Name="StemmerTokenFilter" FullName="Microsoft.Azure.Search.Models.StemmerTokenFilter">
  <TypeSignature Language="C#" Value="public class StemmerTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StemmerTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.StemmerTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class StemmerTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type StemmerTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.StemmerTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            語幹検索フィルターの特定の言語です。 このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Custom-analyzers-in-Azure-Search#TokenFilters" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StemmerTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StemmerTokenFilter.#ctor" />
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
            StemmerTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StemmerTokenFilter (string name, Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage language);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage language) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StemmerTokenFilter.#ctor(System.String,Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, language As StemmerTokenFilterLanguage)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.StemmerTokenFilter : string * Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage -&gt; Microsoft.Azure.Search.Models.StemmerTokenFilter" Usage="new Microsoft.Azure.Search.Models.StemmerTokenFilter (name, language)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="language" Type="Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="language">使用する言語です。 使用可能な値が含まれます: 'アラビア'、'アルメニア'、'バスク語'、'(ブラジル)'、'ブルガリア語'、'カタロニア'、'チェコ語'、'デンマーク'、'オランダ'、'dutchKp'、'english'、'lightEnglish'、'minimalEnglish'、'possessiveEnglish'、'porter2'、'lovins'、'フィンランド'、'lightFinnish'、'フランス語の'、'lightFrench'、'minimalFrench'、'ガリシア'、'minimalGalician'、'ドイツ語'、'german2'、'lightGerman'、'minimalGerman'、'ギリシャ'、'ヒンディー語'、'ハンガリー語'、'lightHungarian'、'インドネシア'、'アイルランド'、'イタリア'、'lightItalian'、'sorani'、'ラトビア語 '、'ノルウェー'、'lightNorwegian'、'minimalNorwegian'、'lightNynorsk'、'minimalNynorsk'、'ポルトガル語-'、'lightPortuguese'、'minimalPortuguese'、'portugueseRslp'、'ルーマニア語'、'ロシア語'、'lightRussian'、'スペイン'、'lightSpanish'、'スウェーデン語 '、'lightSwedish'、'トルコ語'</param>
        <summary>
            StemmerTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Language">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage Language { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage Language" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StemmerTokenFilter.Language" />
      <MemberSignature Language="VB.NET" Value="Public Property Language As StemmerTokenFilterLanguage" />
      <MemberSignature Language="F#" Value="member this.Language : Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage with get, set" Usage="Microsoft.Azure.Search.Models.StemmerTokenFilter.Language" />
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
        <ReturnType>Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用する言語を設定します。 使用可能な値が含まれます: 'アラビア'、'アルメニア'、'バスク語'、'(ブラジル)'、'ブルガリア語'、'カタロニア'、'チェコ語'、'デンマーク'、'オランダ'、'dutchKp'、'english'、'lightEnglish'、'minimalEnglish'、'possessiveEnglish'、'porter2'、'lovins'、'フィンランド'、'lightFinnish'、'フランス語の'、'lightFrench'、'minimalFrench'、'ガリシア'、'minimalGalician'、'ドイツ語'、'german2'、'lightGerman'、'minimalGerman'、'ギリシャ'、'ヒンディー語'、'ハンガリー語'、'lightHungarian'、'インドネシア'、'アイルランド'、'イタリア'、'lightItalian'、'sorani'、'ラトビア語 '、'ノルウェー'、'lightNorwegian'、'minimalNorwegian'、'lightNynorsk'、'minimalNynorsk'、'ポルトガル語-'、'lightPortuguese'、'minimalPortuguese'、'portugueseRslp'、'ルーマニア語'、'ロシア語'、'lightRussian'、'スペイン'、'lightSpanish'、'スウェーデン語 '、'lightSwedish'、'トルコ語'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StemmerTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="stemmerTokenFilter.Validate " />
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