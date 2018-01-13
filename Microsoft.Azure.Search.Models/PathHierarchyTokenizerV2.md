<Type Name="PathHierarchyTokenizerV2" FullName="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2">
  <TypeSignature Language="C#" Value="public class PathHierarchyTokenizerV2 : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PathHierarchyTokenizerV2 extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2" />
  <TypeSignature Language="VB.NET" Value="Public Class PathHierarchyTokenizerV2&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type PathHierarchyTokenizerV2 = class&#xA;    inherit Tokenizer" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PathHierarchyTokenizerV2")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            パスのような階層のトークナイザ。 このトークナイザは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/path/PathHierarchyTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PathHierarchyTokenizerV2 ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.#ctor" />
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
            PathHierarchyTokenizerV2 クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PathHierarchyTokenizerV2 (string name, Nullable&lt;char&gt; delimiter = null, Nullable&lt;char&gt; replacement = null, Nullable&lt;int&gt; maxTokenLength = null, Nullable&lt;bool&gt; reverseTokenOrder = null, Nullable&lt;int&gt; numberOfTokensToSkip = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;char&gt; delimiter, valuetype System.Nullable`1&lt;char&gt; replacement, valuetype System.Nullable`1&lt;int32&gt; maxTokenLength, valuetype System.Nullable`1&lt;bool&gt; reverseTokenOrder, valuetype System.Nullable`1&lt;int32&gt; numberOfTokensToSkip) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.#ctor(System.String,System.Nullable{System.Char},System.Nullable{System.Char},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional delimiter As Nullable(Of Char) = null, Optional replacement As Nullable(Of Char) = null, Optional maxTokenLength As Nullable(Of Integer) = null, Optional reverseTokenOrder As Nullable(Of Boolean) = null, Optional numberOfTokensToSkip As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2 : string * Nullable&lt;char&gt; * Nullable&lt;char&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2" Usage="new Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2 (name, delimiter, replacement, maxTokenLength, reverseTokenOrder, numberOfTokensToSkip)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="delimiter" Type="System.Nullable&lt;System.Char&gt;" />
        <Parameter Name="replacement" Type="System.Nullable&lt;System.Char&gt;" />
        <Parameter Name="maxTokenLength" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="reverseTokenOrder" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="numberOfTokensToSkip" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name">トークナイザの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="delimiter">使用する区切り記号文字。 既定値は「/」です。</param>
        <param name="replacement">A 値の設定、区切り記号の文字を置き換えます。 既定値は「/」です。</param>
        <param name="maxTokenLength">トークンの最大長。 既定値と最大値は、300 です。</param>
        <param name="reverseTokenOrder">逆の順序でトークンを生成するかどうかを示す値。 既定値は false です。</param>
        <param name="numberOfTokensToSkip">スキップする初期のトークンの数。 既定値は 0 です。</param>
        <summary>
            PathHierarchyTokenizerV2 クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public Nullable&lt;char&gt; Delimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;char&gt; Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property Delimiter As Nullable(Of Char)" />
      <MemberSignature Language="F#" Value="member this.Delimiter : Nullable&lt;char&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="delimiter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Char&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用する区切り文字を設定します。 既定値は「/」です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.MaxTokenLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenLength As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenLength : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.MaxTokenLength" />
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
            取得または最大トークン長を設定します。 既定値と最大値は、300 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfTokensToSkip">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfTokensToSkip { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfTokensToSkip" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.NumberOfTokensToSkip" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfTokensToSkip As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfTokensToSkip : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.NumberOfTokensToSkip" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="skip")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスキップする初期のトークンの数を設定します。 既定値は 0 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replacement">
      <MemberSignature Language="C#" Value="public Nullable&lt;char&gt; Replacement { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;char&gt; Replacement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.Replacement" />
      <MemberSignature Language="VB.NET" Value="Public Property Replacement As Nullable(Of Char)" />
      <MemberSignature Language="F#" Value="member this.Replacement : Nullable&lt;char&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.Replacement" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replacement")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Char&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            場合の値を設定を取得または設定、区切り記号の文字を置き換えます。 既定値は「/」です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReverseTokenOrder">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReverseTokenOrder { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReverseTokenOrder" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.ReverseTokenOrder" />
      <MemberSignature Language="VB.NET" Value="Public Property ReverseTokenOrder As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReverseTokenOrder : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.ReverseTokenOrder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reverse")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークンを逆の順序で生成するかどうかを示す値を設定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PathHierarchyTokenizerV2.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="pathHierarchyTokenizerV2.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
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