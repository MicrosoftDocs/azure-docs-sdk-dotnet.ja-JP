<Type Name="TokenizerName" FullName="Microsoft.Azure.Search.Models.TokenizerName">
  <TypeSignature Language="C#" Value="public sealed class TokenizerName : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.TokenizerName&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TokenizerName extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.TokenizerName&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.TokenizerName" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TokenizerName&#xA;Inherits ExtensibleEnum(Of TokenizerName)" />
  <TypeSignature Language="F#" Value="type TokenizerName = class&#xA;    inherit ExtensibleEnum&lt;TokenizerName&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.TokenizerName&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.TokenizerName</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.TokenizerName&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Search でサポートされているすべてのサロゲートの名前を定義します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Custom-analyzers-in-Azure-Search" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Classic">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Classic;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Classic" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Classic" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Classic As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Classic : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Classic" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ほとんどのヨーロッパ言語のドキュメントを処理するために適切な文法ベース トークナイザ。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/standard/ClassicTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.TokenizerName Create (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.TokenizerName Create(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenizerName.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (name As String) As TokenizerName" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Create name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">トークナイザの名前です。</param>
        <summary>
            TokenizerName インスタンスの新規作成または既知のトークナイザの指定した名前に一致する場合に、既存のインスタンスを取得します。
            </summary>
        <returns>指定した名前の TokenizerName インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EdgeNGram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName EdgeNGram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName EdgeNGram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.EdgeNGram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly EdgeNGram As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable EdgeNGram : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.EdgeNGram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            指定されたサイズの n-gram のエッジからの入力をトークン化です。
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/EdgeNGramTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keyword">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Keyword;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Keyword" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Keyword" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Keyword As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Keyword : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Keyword" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            1 つのトークンとして入力全体を出力します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/KeywordTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Letter">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Letter;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Letter" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Letter" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Letter As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Letter : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Letter" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            英字以外でテキストを分割します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/LetterTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lowercase">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Lowercase;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Lowercase" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Lowercase" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Lowercase As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Lowercase : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Lowercase" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            英字以外でテキストを分割し、それらを小文字に変換します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/LowerCaseTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftLanguageStemmingTokenizer">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName MicrosoftLanguageStemmingTokenizer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName MicrosoftLanguageStemmingTokenizer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.MicrosoftLanguageStemmingTokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MicrosoftLanguageStemmingTokenizer As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable MicrosoftLanguageStemmingTokenizer : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.MicrosoftLanguageStemmingTokenizer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            言語固有の規則を使用してテキストを分割し、基本フォームに単語を短縮します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftLanguageTokenizer">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName MicrosoftLanguageTokenizer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName MicrosoftLanguageTokenizer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.MicrosoftLanguageTokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MicrosoftLanguageTokenizer As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable MicrosoftLanguageTokenizer : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.MicrosoftLanguageTokenizer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            言語固有の規則を使用してテキストを分割します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NGram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName NGram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName NGram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.NGram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NGram As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable NGram : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.NGram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            指定されたサイズの n-gram への入力をトークン化です。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/NGramTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.TokenizerName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.TokenizerName op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenizerName.op_Implicit(System.String)~Microsoft.Azure.Search.Models.TokenizerName" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As TokenizerName" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">変換する文字列。</param>
        <summary>
            文字列から TokenizerName への暗黙的な変換を定義します。
            </summary>
        <returns>TokenizerName として文字列です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathHierarchy">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName PathHierarchy;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName PathHierarchy" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.PathHierarchy" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly PathHierarchy As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable PathHierarchy : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.PathHierarchy" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パスのような階層のトークナイザ。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/path/PathHierarchyTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pattern">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Pattern;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Pattern" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Pattern" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Pattern As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Pattern : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Pattern" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            正規表現パターンに一致する個別のトークンを構築するために使用するトークナイザ。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/pattern/PatternTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Standard">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Standard;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Standard" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Standard" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Standard As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Standard : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Standard" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            標準 Lucene アナライザーです。標準トークナイザー、小文字のフィルターおよびフィルターで構成されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/standard/StandardTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UaxUrlEmail">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName UaxUrlEmail;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName UaxUrlEmail" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.UaxUrlEmail" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly UaxUrlEmail As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable UaxUrlEmail : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.UaxUrlEmail" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Url と電子メールを 1 つのトークンとしてトークン化です。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/standard/UAX29URLEmailTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Whitespace">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenizerName Whitespace;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenizerName Whitespace" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenizerName.Whitespace" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Whitespace As TokenizerName " />
      <MemberSignature Language="F#" Value=" staticval mutable Whitespace : Microsoft.Azure.Search.Models.TokenizerName" Usage="Microsoft.Azure.Search.Models.TokenizerName.Whitespace" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            空白文字でテキストを分割します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/WhitespaceTokenizer.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>