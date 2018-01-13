<Type Name="JsonFormat" FullName="Microsoft.Azure.Management.DataFactory.Models.JsonFormat">
  <TypeSignature Language="C#" Value="public class JsonFormat : Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JsonFormat extends Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.JsonFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonFormat&#xA;Inherits DatasetStorageFormat" />
  <TypeSignature Language="F#" Value="type JsonFormat = class&#xA;    inherit DatasetStorageFormat" />
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
            JSON 形式で格納されているデータ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonFormat ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.#ctor" />
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
            JsonFormat クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonFormat (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object serializer = null, object deserializer = null, string filePattern = null, object nestingSeparator = null, object encodingName = null, object jsonNodeReference = null, object jsonPathDefinition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object serializer, object deserializer, string filePattern, object nestingSeparator, object encodingName, object jsonNodeReference, object jsonPathDefinition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.String,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional serializer As Object = null, Optional deserializer As Object = null, Optional filePattern As String = null, Optional nestingSeparator As Object = null, Optional encodingName As Object = null, Optional jsonNodeReference As Object = null, Optional jsonPathDefinition As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.JsonFormat : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * string * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.JsonFormat" Usage="new Microsoft.Azure.Management.DataFactory.Models.JsonFormat (additionalProperties, serializer, deserializer, filePattern, nestingSeparator, encodingName, jsonNodeReference, jsonPathDefinition)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="serializer" Type="System.Object" />
        <Parameter Name="deserializer" Type="System.Object" />
        <Parameter Name="filePattern" Type="System.String" />
        <Parameter Name="nestingSeparator" Type="System.Object" />
        <Parameter Name="encodingName" Type="System.Object" />
        <Parameter Name="jsonNodeReference" Type="System.Object" />
        <Parameter Name="jsonPathDefinition" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="serializer">シリアライザー。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="deserializer">デシリアライザー。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="filePattern">JSON のファイルのパターン。 JSON オブジェクトのコレクションを分割する方法をより具体的になります。 既定値は、'setOfObjects' です。 このコマンドは、大文字小文字を区別します。 使用可能な値が含まれます: 'setOfObjects'、'arrayOfObjects'</param>
        <param name="nestingSeparator">入れ子になったレベルを区切るために使用する文字。 既定値は '.'(ドット)。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="encodingName">使用するエンコーディングのコード ページ名。 指定しない場合、バイト順マーク (BOM) が別の Unicode エンコードを表しますしない限り、既定値は 'utf-8' にします。 次の参照のエンコーディングのテーブルの 'Name' 列でサポートされている値の完全な一覧が見つかりません: https://go.microsoft.com/fwlink/?linkid=861078 です。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="jsonNodeReference">フラット化する JSON 配列要素の JSONPath します。 例:"$ です。ArrayPath"です。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="jsonPathDefinition">JSON ファイルからデータを抽出するカスタマイズされた列名を持つ各列のマッピングの JSONPath 定義します。 ルート オブジェクトの下のフィールドには、「$」; で開始します。jsonNodeReference プロパティが選択した配列内のフィールドには、配列の要素から開始します。 例: {"Column1":"$ です。Column1Path"、"Column2":"Column2PathInArray"}。 型: オブジェクト (または式 resultType オブジェクトを使用)。</param>
        <summary>
            JsonFormat クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodingName">
      <MemberSignature Language="C#" Value="public object EncodingName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncodingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.EncodingName" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodingName As Object" />
      <MemberSignature Language="F#" Value="member this.EncodingName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JsonFormat.EncodingName" />
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
            取得または使用するエンコーディングのコード ページ名を設定します。 指定しない場合、バイト順マーク (BOM) が別の Unicode エンコードを表しますしない限り、既定値は 'utf-8' にします。 次の参照のエンコーディングのテーブルの 'Name' 列でサポートされている値の完全な一覧が見つかりません: https://go.microsoft.com/fwlink/?linkid=861078 です。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePattern">
      <MemberSignature Language="C#" Value="public string FilePattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.FilePattern" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePattern As String" />
      <MemberSignature Language="F#" Value="member this.FilePattern : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JsonFormat.FilePattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または JSON のファイルのパターンを設定します。 JSON オブジェクトのコレクションを分割する方法をより具体的になります。 既定値は、'setOfObjects' です。 このコマンドは、大文字小文字を区別します。 使用可能な値が含まれます: 'setOfObjects'、'arrayOfObjects'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonNodeReference">
      <MemberSignature Language="C#" Value="public object JsonNodeReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object JsonNodeReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.JsonNodeReference" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonNodeReference As Object" />
      <MemberSignature Language="F#" Value="member this.JsonNodeReference : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JsonFormat.JsonNodeReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jsonNodeReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフラット化する JSON 配列要素の JSONPath を設定します。 例:"$ です。ArrayPath"です。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonPathDefinition">
      <MemberSignature Language="C#" Value="public object JsonPathDefinition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object JsonPathDefinition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.JsonPathDefinition" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonPathDefinition As Object" />
      <MemberSignature Language="F#" Value="member this.JsonPathDefinition : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JsonFormat.JsonPathDefinition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jsonPathDefinition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または JSON ファイルからデータを抽出するカスタマイズされた列名を持つ各列のマッピングの JSONPath 定義を設定します。 ルート オブジェクトの下のフィールドには、「$」; で開始します。jsonNodeReference プロパティが選択した配列内のフィールドには、配列の要素から開始します。
            例: {"Column1":"$ です。Column1Path"、"Column2":"Column2PathInArray"}。 型: オブジェクト (または式 resultType オブジェクトを使用)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NestingSeparator">
      <MemberSignature Language="C#" Value="public object NestingSeparator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object NestingSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.NestingSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Property NestingSeparator As Object" />
      <MemberSignature Language="F#" Value="member this.NestingSeparator : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JsonFormat.NestingSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nestingSeparator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または入れ子になったレベルを区切るために使用する文字を設定します。 既定値は '.'(ドット)。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>