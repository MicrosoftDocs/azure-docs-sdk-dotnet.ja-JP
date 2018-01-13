<Type Name="TextFormat" FullName="Microsoft.Azure.Management.DataFactory.Models.TextFormat">
  <TypeSignature Language="C#" Value="public class TextFormat : Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TextFormat extends Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.TextFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class TextFormat&#xA;Inherits DatasetStorageFormat" />
  <TypeSignature Language="F#" Value="type TextFormat = class&#xA;    inherit DatasetStorageFormat" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            テキスト形式で格納されているデータ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TextFormat ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TextFormat.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TextFormat クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TextFormat (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object serializer = null, object deserializer = null, object columnDelimiter = null, object rowDelimiter = null, object escapeChar = null, object quoteChar = null, object nullValue = null, object encodingName = null, object treatEmptyAsNull = null, object skipLineCount = null, object firstRowAsHeader = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object serializer, object deserializer, object columnDelimiter, object rowDelimiter, object escapeChar, object quoteChar, object nullValue, object encodingName, object treatEmptyAsNull, object skipLineCount, object firstRowAsHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TextFormat.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional serializer As Object = null, Optional deserializer As Object = null, Optional columnDelimiter As Object = null, Optional rowDelimiter As Object = null, Optional escapeChar As Object = null, Optional quoteChar As Object = null, Optional nullValue As Object = null, Optional encodingName As Object = null, Optional treatEmptyAsNull As Object = null, Optional skipLineCount As Object = null, Optional firstRowAsHeader As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.TextFormat : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.TextFormat" Usage="new Microsoft.Azure.Management.DataFactory.Models.TextFormat (additionalProperties, serializer, deserializer, columnDelimiter, rowDelimiter, escapeChar, quoteChar, nullValue, encodingName, treatEmptyAsNull, skipLineCount, firstRowAsHeader)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="serializer" Type="System.Object" />
        <Parameter Name="deserializer" Type="System.Object" />
        <Parameter Name="columnDelimiter" Type="System.Object" />
        <Parameter Name="rowDelimiter" Type="System.Object" />
        <Parameter Name="escapeChar" Type="System.Object" />
        <Parameter Name="quoteChar" Type="System.Object" />
        <Parameter Name="nullValue" Type="System.Object" />
        <Parameter Name="encodingName" Type="System.Object" />
        <Parameter Name="treatEmptyAsNull" Type="System.Object" />
        <Parameter Name="skipLineCount" Type="System.Object" />
        <Parameter Name="firstRowAsHeader" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="serializer">シリアライザー。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="deserializer">デシリアライザー。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="columnDelimiter">列の区切り記号。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="rowDelimiter">行区切り記号です。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="escapeChar">エスケープ文字。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="quoteChar">引用符文字。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="nullValue">Null 値の文字列。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="encodingName">使用するエンコーディングのコード ページ名。 かどうかミス、既定値は ΓÇ £utf 8ΓÇ ¥ 限り BOM は、Unicode、別のエンコードを表します。 サポートされている値を設定する次のリンク内のテーブルの ΓÇ £NameΓÇ ¥ 列を参照してください: https://msdn.microsoft.com/library/system.text.encoding.aspx です。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="treatEmptyAsNull">テキスト ファイルに空の列の値を null として扱います。 既定値は true です。 型: ブール値 (または式の resultType ブール値)。</param>
        <param name="skipLineCount">テキスト ファイルの解析中にスキップするには、行/行の数。 既定値は 0 です。 型: 整数 (または式に整数の resultType)。</param>
        <param name="firstRowAsHeader">入力として使用する場合は、データの最初の行をヘッダーとして扱います。 出力として使用する場合は、データの最初の行として出力に、ヘッダーを書き込みます。 既定値は false です。
            型: ブール値 (または式の resultType ブール値)。</param>
        <summary>
            TextFormat クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnDelimiter">
      <MemberSignature Language="C#" Value="public object ColumnDelimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ColumnDelimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TextFormat.ColumnDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property ColumnDelimiter As Object" />
      <MemberSignature Language="F#" Value="member this.ColumnDelimiter : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TextFormat.ColumnDelimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columnDelimiter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または列の区切り記号を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodingName">
      <MemberSignature Language="C#" Value="public object EncodingName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncodingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TextFormat.EncodingName" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodingName As Object" />
      <MemberSignature Language="F#" Value="member this.EncodingName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TextFormat.EncodingName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encodingName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用するエンコーディングのコード ページ名を設定します。 かどうかミス、既定値は ΓÇ £utf 8ΓÇ ¥ 限り BOM は、Unicode、別のエンコードを表します。 サポートされている値を設定する次のリンク内のテーブルの ΓÇ £NameΓÇ ¥ 列を参照してください: https://msdn.microsoft.com/library/system.text.encoding.aspx です。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EscapeChar">
      <MemberSignature Language="C#" Value="public object EscapeChar { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EscapeChar" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TextFormat.EscapeChar" />
      <MemberSignature Language="VB.NET" Value="Public Property EscapeChar As Object" />
      <MemberSignature Language="F#" Value="member this.EscapeChar : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TextFormat.EscapeChar" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="escapeChar")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエスケープ文字を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirstRowAsHeader">
      <MemberSignature Language="C#" Value="public object FirstRowAsHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FirstRowAsHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TextFormat.FirstRowAsHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property FirstRowAsHeader As Object" />
      <MemberSignature Language="F#" Value="member this.FirstRowAsHeader : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TextFormat.FirstRowAsHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="firstRowAsHeader")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定として入力、扱うデータの最初の行ヘッダーとして使用する場合。 出力として使用する場合は、データの最初の行として出力に、ヘッダーを書き込みます。 既定値は false です。 型: ブール値 (または式の resultType ブール値)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NullValue">
      <MemberSignature Language="C#" Value="public object NullValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object NullValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TextFormat.NullValue" />
      <MemberSignature Language="VB.NET" Value="Public Property NullValue As Object" />
      <MemberSignature Language="F#" Value="member this.NullValue : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TextFormat.NullValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nullValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または null 値の文字列を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuoteChar">
      <MemberSignature Language="C#" Value="public object QuoteChar { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object QuoteChar" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TextFormat.QuoteChar" />
      <MemberSignature Language="VB.NET" Value="Public Property QuoteChar As Object" />
      <MemberSignature Language="F#" Value="member this.QuoteChar : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TextFormat.QuoteChar" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quoteChar")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または引用文字を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowDelimiter">
      <MemberSignature Language="C#" Value="public object RowDelimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RowDelimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TextFormat.RowDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property RowDelimiter As Object" />
      <MemberSignature Language="F#" Value="member this.RowDelimiter : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TextFormat.RowDelimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rowDelimiter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または行区切り記号を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipLineCount">
      <MemberSignature Language="C#" Value="public object SkipLineCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SkipLineCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TextFormat.SkipLineCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipLineCount As Object" />
      <MemberSignature Language="F#" Value="member this.SkipLineCount : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TextFormat.SkipLineCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="skipLineCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはテキスト ファイルの解析中にスキップするには、行/行の数を設定します。 既定値は 0 です。 型: 整数 (または式に整数の resultType)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TreatEmptyAsNull">
      <MemberSignature Language="C#" Value="public object TreatEmptyAsNull { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TreatEmptyAsNull" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TextFormat.TreatEmptyAsNull" />
      <MemberSignature Language="VB.NET" Value="Public Property TreatEmptyAsNull As Object" />
      <MemberSignature Language="F#" Value="member this.TreatEmptyAsNull : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TextFormat.TreatEmptyAsNull" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="treatEmptyAsNull")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、テキスト ファイルに空の列の値を null として扱います。
            既定値は true です。 型: ブール値 (または式の resultType ブール値)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>