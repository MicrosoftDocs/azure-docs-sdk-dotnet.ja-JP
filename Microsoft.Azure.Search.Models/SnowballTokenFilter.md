<Type Name="SnowballTokenFilter" FullName="Microsoft.Azure.Search.Models.SnowballTokenFilter">
  <TypeSignature Language="C#" Value="public class SnowballTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SnowballTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SnowballTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class SnowballTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type SnowballTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.SnowballTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Snowball で生成されたステマーを使用して単語を生じるフィルターです。 このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/snowball/SnowballFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SnowballTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SnowballTokenFilter.#ctor" />
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
            SnowballTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SnowballTokenFilter (string name, Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage language);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage language) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SnowballTokenFilter.#ctor(System.String,Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, language As SnowballTokenFilterLanguage)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SnowballTokenFilter : string * Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage -&gt; Microsoft.Azure.Search.Models.SnowballTokenFilter" Usage="new Microsoft.Azure.Search.Models.SnowballTokenFilter (name, language)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="language" Type="Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="language">使用する言語です。 使用可能な値が含まれます: 'アルメニア'、'バスク語'、'カタロニア'、'デンマーク'、'オランダ'、'english'、'フィンランド'、'フランス語の'、'ドイツ語'、'german2'、'ハンガリー語'、'イタリア語'、'kp'、'lovins'、'ノルウェー'、'porter'、'ポルトガル語'、'ルーマニア語'、'ロシア語'、'スペイン語'、'スウェーデン語 '、'トルコ語'</param>
        <summary>
            SnowballTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Language">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage Language { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage Language" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SnowballTokenFilter.Language" />
      <MemberSignature Language="VB.NET" Value="Public Property Language As SnowballTokenFilterLanguage" />
      <MemberSignature Language="F#" Value="member this.Language : Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage with get, set" Usage="Microsoft.Azure.Search.Models.SnowballTokenFilter.Language" />
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
        <ReturnType>Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用する言語を設定します。 使用可能な値が含まれます: 'アルメニア'、'バスク語'、'カタロニア'、'デンマーク'、'オランダ'、'english'、'フィンランド'、'フランス語の'、'ドイツ語'、'german2'、'ハンガリー語'、'イタリア語'、'kp'、'lovins'、'ノルウェー'、'porter'、'ポルトガル語'、'ルーマニア語'、'ロシア語'、'スペイン語'、'スウェーデン語 '、'トルコ語'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SnowballTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="snowballTokenFilter.Validate " />
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