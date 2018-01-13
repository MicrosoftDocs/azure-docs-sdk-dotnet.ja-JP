<Type Name="TokenFilterName" FullName="Microsoft.Azure.Search.Models.TokenFilterName">
  <TypeSignature Language="C#" Value="public sealed class TokenFilterName : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TokenFilterName extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.TokenFilterName" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TokenFilterName&#xA;Inherits ExtensibleEnum(Of TokenFilterName)" />
  <TypeSignature Language="F#" Value="type TokenFilterName = class&#xA;    inherit ExtensibleEnum&lt;TokenFilterName&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.TokenFilterName</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Search でサポートされているすべてのトークンのフィルターの名前を定義します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Custom-analyzers-in-Azure-Search" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Apostrophe">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Apostrophe;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Apostrophe" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Apostrophe" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Apostrophe As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Apostrophe : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Apostrophe" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アポストロフィ (アポストロフィ自体を含む) の後にすべての文字を削除します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/tr/ApostropheFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ArabicNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName ArabicNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName ArabicNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.ArabicNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly ArabicNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable ArabicNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.ArabicNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トークンのフィルターを orthography を正規化するアラビア語のノーマライザーを適用します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ar/ArabicNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsciiFolding">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName AsciiFolding;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName AsciiFolding" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.AsciiFolding" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly AsciiFolding As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable AsciiFolding : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.AsciiFolding" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このような対応が存在しない場合は、アルファベット、数字、および記号の Unicode 文字の最初の 127 ASCII 文字 (Unicode の「基本的なラテン」ブロック) ではない、ASCII 値に変換します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/ASCIIFoldingFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CjkBigram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName CjkBigram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName CjkBigram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.CjkBigram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly CjkBigram As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable CjkBigram : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.CjkBigram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            StandardTokenizer から生成される CJK 用語の字を形成します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/cjk/CJKBigramFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CjkWidth">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName CjkWidth;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName CjkWidth" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.CjkWidth" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly CjkWidth As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable CjkWidth : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.CjkWidth" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            CJK 幅の違いを正規化します。 等価の基本的なラテンにフォールド全角 ASCII バリアントと同等のかなに半角カタカナ バリアントではします。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/cjk/CJKWidthFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Classic">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Classic;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Classic" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Classic" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Classic As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Classic : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Classic" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            英語所有格を削除し、頭字語からドットします。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/standard/ClassicFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonGram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName CommonGram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName CommonGram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.CommonGram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly CommonGram As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable CommonGram : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.CommonGram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インデックス作成中に条件を頻繁に発生したため bigram を構築します。
            1 つの用語のインデックス処理がすぎる、bigram オーバーレイにします。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/commongrams/CommonGramsFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.TokenFilterName Create (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.TokenFilterName Create(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenFilterName.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (name As String) As TokenFilterName" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Create name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前です。</param>
        <summary>
            TokenFilterName インスタンスの新規作成または指定された名前と一致する既知のトークン フィルターの場合は、既存のインスタンスを返します。
            </summary>
        <returns>指定した名前の TokenFilterName インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EdgeNGram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName EdgeNGram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName EdgeNGram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.EdgeNGram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly EdgeNGram As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable EdgeNGram : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.EdgeNGram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            N-gram の前面または入力トークンの背面から指定されたサイズが生成されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/EdgeNGramTokenFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Elision">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Elision;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Elision" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Elision" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Elision As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Elision : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Elision" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略記号を削除します。 たとえば、"l'avion"(平面) は、"avion"(平面) に変換されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/util/ElisionFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GermanNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName GermanNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName GermanNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.GermanNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly GermanNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable GermanNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.GermanNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このヒューリスティックでは、German2 snowball アルゴリズムのに従ってドイツ語の文字を正規化します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/de/GermanNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HindiNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName HindiNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName HindiNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.HindiNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly HindiNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable HindiNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.HindiNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            スペルのバリエーションのいくつかの違いを削除するヒンディー語のテキストを正規化します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/hi/HindiNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndicNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName IndicNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName IndicNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.IndicNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly IndicNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable IndicNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.IndicNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インドの言語でテキストの Unicode 表現を正規化します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/in/IndicNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeywordRepeat">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName KeywordRepeat;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName KeywordRepeat" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.KeywordRepeat" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly KeywordRepeat As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable KeywordRepeat : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.KeywordRepeat" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            1 回キーワードと 1 回としてキーワードではない 2 回、各受信トークンを出力します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/KeywordRepeatFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KStem">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName KStem;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName KStem" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.KStem" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly KStem As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable KStem : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.KStem" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            英語向けの高パフォーマンス kstem フィルターです。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/en/KStemFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Length;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Length" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Length" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Length As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Length : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Length" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            または短すぎるすぎる単語を削除します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/LengthFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Limit;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Limit" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Limit As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Limit : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Limit" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インデックス作成中に、トークンの数を制限します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/LimitTokenCountFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lowercase">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Lowercase;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Lowercase" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Lowercase" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Lowercase As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Lowercase : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Lowercase" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トークンのテキストを小文字を正規化します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/LowerCaseFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NGram">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName NGram;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName NGram" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.NGram" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NGram As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable NGram : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.NGram" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            指定されたサイズの n-gram を生成します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/NGramTokenFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.TokenFilterName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.TokenFilterName op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TokenFilterName.op_Implicit(System.String)~Microsoft.Azure.Search.Models.TokenFilterName" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As TokenFilterName" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">変換する文字列。</param>
        <summary>
            文字列から TokenFilterName への暗黙的な変換を定義します。
            </summary>
        <returns>TokenFilterName として文字列です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PersianNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName PersianNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName PersianNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.PersianNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly PersianNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable PersianNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.PersianNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ペルシア語の正規化を適用します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/fa/PersianNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Phonetic">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Phonetic;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Phonetic" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Phonetic" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Phonetic As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Phonetic : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Phonetic" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ルビの一致のトークンを作成します。
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-phonetic/org/apache/lucene/analysis/phonetic/package-tree.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PorterStem">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName PorterStem;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName PorterStem" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.PorterStem" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly PorterStem As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable PorterStem : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.PorterStem" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Porter 語幹検索アルゴリズムを使用して、トークンのストリームを変換します。
            <see href="http://tartarus.org/~martin/PorterStemmer/" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reverse">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Reverse;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Reverse" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Reverse" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Reverse As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Reverse : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Reverse" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トークンの文字列を反転させます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/reverse/ReverseStringFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScandinavianFoldingNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName ScandinavianFoldingNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName ScandinavianFoldingNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.ScandinavianFoldingNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly ScandinavianFoldingNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable ScandinavianFoldingNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.ScandinavianFoldingNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            複数の折りたたみますスカンジナビア語の文字 åÅäæÄÆ -&gt;と öÖøØ-&gt;o です。 二重の母音の使用に対してもで区別 aa、ae、ao、oe およびオブジェクト指向、最初の 1 つだけのままです。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/ScandinavianFoldingFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScandinavianNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName ScandinavianNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName ScandinavianNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.ScandinavianNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly ScandinavianNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable ScandinavianNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.ScandinavianNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            交換可能スカンジナビア語の文字の使用を正規化します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/ScandinavianNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Shingle">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Shingle;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Shingle" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Shingle" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Shingle As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Shingle : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Shingle" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            1 つのトークンとトークンの組み合わせを作成します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/shingle/ShingleFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snowball">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Snowball;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Snowball" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Snowball" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Snowball As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Snowball : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Snowball" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Snowball で生成されたステマーを使用して単語を生じるフィルターです。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/snowball/SnowballFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SoraniNormalization">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName SoraniNormalization;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName SoraniNormalization" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.SoraniNormalization" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly SoraniNormalization As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable SoraniNormalization : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.SoraniNormalization" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Sorani テキストの Unicode 表現を正規化します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ckb/SoraniNormalizationFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stemmer">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Stemmer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Stemmer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Stemmer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Stemmer As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Stemmer : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Stemmer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            語幹検索フィルターの特定の言語です。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Custom-analyzers-in-Azure-Search#TokenFilters" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stopwords">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Stopwords;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Stopwords" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Stopwords" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Stopwords As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Stopwords : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Stopwords" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            削除は、トークンのストリームから単語を停止します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/StopFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Trim">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Trim;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Trim" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Trim" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Trim As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Trim : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Trim" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            先頭および末尾のトークンからの空白をトリミングします。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/TrimFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Truncate">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Truncate;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Truncate" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Truncate" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Truncate As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Truncate : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Truncate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            特定の長さに用語を切り捨てます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/TruncateTokenFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unique">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Unique;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Unique" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Unique" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Unique As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Unique : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Unique" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            以前のトークンと同じテキストでトークンが除外されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/RemoveDuplicatesTokenFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uppercase">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName Uppercase;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName Uppercase" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.Uppercase" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Uppercase As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable Uppercase : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.Uppercase" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トークンのテキストを大文字に正規化します。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/UpperCaseFilter.html" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WordDelimiter">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.TokenFilterName WordDelimiter;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.TokenFilterName WordDelimiter" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.TokenFilterName.WordDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly WordDelimiter As TokenFilterName " />
      <MemberSignature Language="F#" Value=" staticval mutable WordDelimiter : Microsoft.Azure.Search.Models.TokenFilterName" Usage="Microsoft.Azure.Search.Models.TokenFilterName.WordDelimiter" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenFilterName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Subwords に単語を分割し、subword グループに対して省略可能な変換を実行します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>