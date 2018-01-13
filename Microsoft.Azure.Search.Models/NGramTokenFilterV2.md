<Type Name="NGramTokenFilterV2" FullName="Microsoft.Azure.Search.Models.NGramTokenFilterV2">
  <TypeSignature Language="C#" Value="public class NGramTokenFilterV2 : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NGramTokenFilterV2 extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.NGramTokenFilterV2" />
  <TypeSignature Language="VB.NET" Value="Public Class NGramTokenFilterV2&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type NGramTokenFilterV2 = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.NGramTokenFilterV2")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            指定されたサイズの n-gram を生成します。 このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/NGramTokenFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NGramTokenFilterV2 ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenFilterV2.#ctor" />
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
            NGramTokenFilterV2 クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NGramTokenFilterV2 (string name, Nullable&lt;int&gt; minGram = null, Nullable&lt;int&gt; maxGram = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; minGram, valuetype System.Nullable`1&lt;int32&gt; maxGram) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenFilterV2.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional minGram As Nullable(Of Integer) = null, Optional maxGram As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.NGramTokenFilterV2 : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.NGramTokenFilterV2" Usage="new Microsoft.Azure.Search.Models.NGramTokenFilterV2 (name, minGram, maxGram)" />
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
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="minGram">最小 n グラム長。 既定値は 1 です。
            最大値は、300 です。 MaxGram の値よりも小さい必要があります。</param>
        <param name="maxGram">N グラムの最大長。 既定値は 2 です。
            最大値は、300 です。</param>
        <summary>
            NGramTokenFilterV2 クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.NGramTokenFilterV2.MaxGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.NGramTokenFilterV2.MaxGram" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.NGramTokenFilterV2.MinGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MinGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.NGramTokenFilterV2.MinGram" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenFilterV2.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="nGramTokenFilterV2.Validate " />
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