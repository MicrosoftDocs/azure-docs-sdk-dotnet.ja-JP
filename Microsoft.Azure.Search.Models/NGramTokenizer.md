<Type Name="NGramTokenizer" FullName="Microsoft.Azure.Search.Models.NGramTokenizer">
  <TypeSignature Language="C#" Value="public class NGramTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NGramTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.NGramTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class NGramTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type NGramTokenizer = class&#xA;    inherit Tokenizer" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.NGramTokenizer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            指定されたサイズの n-gram への入力をトークン化です。 このトークナイザは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/NGramTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NGramTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenizer.#ctor" />
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
            NGramTokenizer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NGramTokenizer (string name, Nullable&lt;int&gt; minGram = null, Nullable&lt;int&gt; maxGram = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt; tokenChars = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; minGram, valuetype System.Nullable`1&lt;int32&gt; maxGram, class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Search.Models.TokenCharacterKind&gt; tokenChars) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenizer.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.TokenCharacterKind})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional minGram As Nullable(Of Integer) = null, Optional maxGram As Nullable(Of Integer) = null, Optional tokenChars As IList(Of TokenCharacterKind) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.NGramTokenizer : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt; -&gt; Microsoft.Azure.Search.Models.NGramTokenizer" Usage="new Microsoft.Azure.Search.Models.NGramTokenizer (name, minGram, maxGram, tokenChars)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="minGram" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxGram" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="tokenChars" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt;" />
      </Parameters>
      <Docs>
        <param name="name">トークナイザの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="minGram">最小 n グラム長。 既定値は 1 です。
            最大値は、300 です。 MaxGram の値よりも小さい必要があります。</param>
        <param name="maxGram">N グラムの最大長。 既定値は 2 です。
            最大値は、300 です。</param>
        <param name="tokenChars">文字クラス トークン内に維持します。</param>
        <summary>
            NGramTokenizer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.NGramTokenizer.MaxGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.NGramTokenizer.MaxGram" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxGram")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または n グラムの最大の長さを設定します。 既定値は 2 です。 最大値は
            300.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.NGramTokenizer.MinGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MinGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.NGramTokenizer.MinGram" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minGram")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または n グラムの最小の長さを設定します。 既定値は 1 です。 最大値は
            300. MaxGram の値よりも小さい必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenChars">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt; TokenChars { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Search.Models.TokenCharacterKind&gt; TokenChars" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.NGramTokenizer.TokenChars" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenChars As IList(Of TokenCharacterKind)" />
      <MemberSignature Language="F#" Value="member this.TokenChars : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt; with get, set" Usage="Microsoft.Azure.Search.Models.NGramTokenizer.TokenChars" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenChars")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenCharacterKind&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークンに保持する文字クラスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="nGramTokenizer.Validate " />
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