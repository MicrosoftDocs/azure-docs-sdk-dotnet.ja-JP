<Type Name="WordDelimiterTokenFilter" FullName="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter">
  <TypeSignature Language="C#" Value="public class WordDelimiterTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WordDelimiterTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class WordDelimiterTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type WordDelimiterTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.WordDelimiterTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Subwords に単語を分割し、subword グループに対して省略可能な変換を実行します。 このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/WordDelimiterFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WordDelimiterTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.#ctor" />
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
            WordDelimiterTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WordDelimiterTokenFilter (string name, Nullable&lt;bool&gt; generateWordParts = null, Nullable&lt;bool&gt; generateNumberParts = null, Nullable&lt;bool&gt; catenateWords = null, Nullable&lt;bool&gt; catenateNumbers = null, Nullable&lt;bool&gt; catenateAll = null, Nullable&lt;bool&gt; splitOnCaseChange = null, Nullable&lt;bool&gt; preserveOriginal = null, Nullable&lt;bool&gt; splitOnNumerics = null, Nullable&lt;bool&gt; stemEnglishPossessive = null, System.Collections.Generic.IList&lt;string&gt; protectedWords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; generateWordParts, valuetype System.Nullable`1&lt;bool&gt; generateNumberParts, valuetype System.Nullable`1&lt;bool&gt; catenateWords, valuetype System.Nullable`1&lt;bool&gt; catenateNumbers, valuetype System.Nullable`1&lt;bool&gt; catenateAll, valuetype System.Nullable`1&lt;bool&gt; splitOnCaseChange, valuetype System.Nullable`1&lt;bool&gt; preserveOriginal, valuetype System.Nullable`1&lt;bool&gt; splitOnNumerics, valuetype System.Nullable`1&lt;bool&gt; stemEnglishPossessive, class System.Collections.Generic.IList`1&lt;string&gt; protectedWords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.#ctor(System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional generateWordParts As Nullable(Of Boolean) = null, Optional generateNumberParts As Nullable(Of Boolean) = null, Optional catenateWords As Nullable(Of Boolean) = null, Optional catenateNumbers As Nullable(Of Boolean) = null, Optional catenateAll As Nullable(Of Boolean) = null, Optional splitOnCaseChange As Nullable(Of Boolean) = null, Optional preserveOriginal As Nullable(Of Boolean) = null, Optional splitOnNumerics As Nullable(Of Boolean) = null, Optional stemEnglishPossessive As Nullable(Of Boolean) = null, Optional protectedWords As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.WordDelimiterTokenFilter : string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.WordDelimiterTokenFilter" Usage="new Microsoft.Azure.Search.Models.WordDelimiterTokenFilter (name, generateWordParts, generateNumberParts, catenateWords, catenateNumbers, catenateAll, splitOnCaseChange, preserveOriginal, splitOnNumerics, stemEnglishPossessive, protectedWords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="generateWordParts" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="generateNumberParts" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="catenateWords" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="catenateNumbers" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="catenateAll" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="splitOnCaseChange" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="preserveOriginal" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="splitOnNumerics" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="stemEnglishPossessive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="protectedWords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="generateWordParts">一部の単語を生成するかどうかを示す値。 場合に生成する単語の原因の一部を設定します。たとえば"AzureSearch"では、"Azure"「検索」になります。 既定値は true です。</param>
        <param name="generateNumberParts">番号 subwords を生成するかどうかを示す値。 既定値は true です。</param>
        <param name="catenateWords">Word 部分の最大の実行を catenated があるかどうかを示す値。 たとえば、この設定は true の場合、"Azure Search"が"AzureSearch"です。 既定値は false です。</param>
        <param name="catenateNumbers">番号の部分の最大値が実行されるかどうかを示す値が catenated されます。 たとえば、true の場合、「1-2」に設定されている場合は、「12」をなります。 既定値は false です。</param>
        <param name="catenateAll">すべての subword 部分が catenated するかどうかを示す値。 たとえば、この設定は true の場合、「Azure-検索-1」が"AzureSearch1"です。 既定値は false です。</param>
        <param name="splitOnCaseChange">CaseChange で単語を分割するかどうかを示す値。 たとえば、この設定は true の場合、"AzureSearch"が"Azure""Search"です。 既定値は true です。</param>
        <param name="preserveOriginal">元の単語が保持され、subword 一覧に追加するかどうかを示す値。 既定値は false です。</param>
        <param name="splitOnNumerics">数値に分割するかどうかを示す値。 たとえば、この設定は true の場合、"Azure1Search"が「1」の"Azure"「検索」です。 既定値は true です。</param>
        <param name="stemEnglishPossessive">各 subword の末尾に「の」を削除するかどうかを示す値。 既定値は true です。</param>
        <param name="protectedWords">区切られたされてから保護するトークンの一覧です。</param>
        <summary>
            WordDelimiterTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatenateAll">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CatenateAll { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CatenateAll" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateAll" />
      <MemberSignature Language="VB.NET" Value="Public Property CatenateAll As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CatenateAll : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateAll" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catenateAll")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または subword のすべての部分を catenated があるかどうかを示す値を設定します。 たとえば、この設定は true の場合、「Azure-検索-1」が"AzureSearch1"です。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatenateNumbers">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CatenateNumbers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CatenateNumbers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateNumbers" />
      <MemberSignature Language="VB.NET" Value="Public Property CatenateNumbers As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CatenateNumbers : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateNumbers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catenateNumbers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または番号の部分の最大の実行を catenated があるかどうかを示す値を設定します。 たとえば、true の場合、「1-2」に設定されている場合は、「12」をなります。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CatenateWords">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CatenateWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CatenateWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateWords" />
      <MemberSignature Language="VB.NET" Value="Public Property CatenateWords As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CatenateWords : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.CatenateWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="catenateWords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または word 部分の最大の実行を catenated があるかどうかを示す値を設定します。 たとえば、この設定は true の場合、"Azure Search"が"AzureSearch"です。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateNumberParts">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateNumberParts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateNumberParts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateNumberParts" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateNumberParts As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateNumberParts : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateNumberParts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="generateNumberParts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または番号 subwords を生成するかどうかを示す値を設定します。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateWordParts">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateWordParts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateWordParts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateWordParts" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateWordParts As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateWordParts : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.GenerateWordParts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="generateWordParts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または一部の単語を生成するかどうかを示す値を設定します。 場合に生成する単語の原因の一部を設定します。たとえば"AzureSearch"では、"Azure"「検索」になります。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreserveOriginal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PreserveOriginal { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PreserveOriginal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.PreserveOriginal" />
      <MemberSignature Language="VB.NET" Value="Public Property PreserveOriginal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PreserveOriginal : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.PreserveOriginal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preserveOriginal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または元の単語が保持され、subword 一覧に追加するかどうかを示す値を設定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedWords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ProtectedWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ProtectedWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.ProtectedWords" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedWords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ProtectedWords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.ProtectedWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedWords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定されている区切りから保護するトークンの一覧。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SplitOnCaseChange">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SplitOnCaseChange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SplitOnCaseChange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnCaseChange" />
      <MemberSignature Language="VB.NET" Value="Public Property SplitOnCaseChange As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SplitOnCaseChange : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnCaseChange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="splitOnCaseChange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または caseChange で単語を分割するかどうかを示す値を設定します。 たとえば、この設定は true の場合、"AzureSearch"が"Azure""Search"です。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SplitOnNumerics">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SplitOnNumerics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SplitOnNumerics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnNumerics" />
      <MemberSignature Language="VB.NET" Value="Public Property SplitOnNumerics As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SplitOnNumerics : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.SplitOnNumerics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="splitOnNumerics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または数字で分割するかどうかを示す値を設定します。 たとえば、この設定は true の場合、"Azure1Search"が「1」の"Azure"「検索」です。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StemEnglishPossessive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; StemEnglishPossessive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; StemEnglishPossessive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.StemEnglishPossessive" />
      <MemberSignature Language="VB.NET" Value="Public Property StemEnglishPossessive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.StemEnglishPossessive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.StemEnglishPossessive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stemEnglishPossessive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または各 subword の末尾に「の」を削除するかどうかを示す値を設定します。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.WordDelimiterTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="wordDelimiterTokenFilter.Validate " />
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