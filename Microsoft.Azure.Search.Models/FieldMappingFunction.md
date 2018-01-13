<Type Name="FieldMappingFunction" FullName="Microsoft.Azure.Search.Models.FieldMappingFunction">
  <TypeSignature Language="C#" Value="public class FieldMappingFunction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FieldMappingFunction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.FieldMappingFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class FieldMappingFunction" />
  <TypeSignature Language="F#" Value="type FieldMappingFunction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            インデックスを作成する前に、データ ソースから値を変換する関数を表します。
            <see href="https://docs.microsoft.com/azure/search/search-indexer-field-mappings" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FieldMappingFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.#ctor" />
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
            FieldMappingFunction クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FieldMappingFunction (string name, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional parameters As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.FieldMappingFunction : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Search.Models.FieldMappingFunction" Usage="new Microsoft.Azure.Search.Models.FieldMappingFunction (name, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="name">フィールド マッピングの関数の名前。</param>
        <param name="parameters">関数に渡すパラメーターの名前/値ペアのディクショナリ。 各値は、プリミティブ型でなければなりません。</param>
        <summary>
            FieldMappingFunction クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Base64Decode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.FieldMappingFunction Base64Decode ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.FieldMappingFunction Base64Decode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.Base64Decode" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Base64Decode () As FieldMappingFunction" />
      <MemberSignature Language="F#" Value="static member Base64Decode : unit -&gt; Microsoft.Azure.Search.Models.FieldMappingFunction" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.Base64Decode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FieldMappingFunction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            入力文字列の Base64 をデコードすることを実行するフィールドのマッピング関数を作成します。 入力は、URL セーフな Base64 でエンコードされた文字列と見なされます。 
            </summary>
        <returns>新しいフィールドのマッピング関数です。</returns>
        <remarks>
            ユース ケースのサンプル: Blob のカスタム メタデータの値は、ASCII エンコードする必要があります。 Base64 エンコードを使用して、BLOB のカスタム メタデータ内の任意の Unicode 文字列を表すことができます。 ただし、意味のある検索を行うために、検索インデックスを設定する際に、エンコードされたデータを "通常の" 文字列に戻すときにこの関数を使用できます。 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Base64Encode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.FieldMappingFunction Base64Encode ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.FieldMappingFunction Base64Encode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.Base64Encode" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Base64Encode () As FieldMappingFunction" />
      <MemberSignature Language="F#" Value="static member Base64Encode : unit -&gt; Microsoft.Azure.Search.Models.FieldMappingFunction" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.Base64Encode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FieldMappingFunction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            入力文字列の URL セーフな Base64 エンコードを実行するフィールドのマッピング関数を作成します。 入力は UTF-8 でエンコードされていることを前提としています。
            </summary>
        <returns>新しいフィールドのマッピング関数です。</returns>
        <remarks>
            ユース ケースのサンプル: (お客様は、API を使用して、参照、たとえば、ドキュメントに対応できる必要があります) ために、Azure Search ドキュメント キーにのみ URL セーフな文字が表示ことができます。 データに URL の安全でない文字が含まれ、それを使用して検索インデックスにキー フィールドを設定する場合に、この関数を使用します。 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtractTokenAtPosition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.FieldMappingFunction ExtractTokenAtPosition (string delimiter, int position);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.FieldMappingFunction ExtractTokenAtPosition(string delimiter, int32 position) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.ExtractTokenAtPosition(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ExtractTokenAtPosition (delimiter As String, position As Integer) As FieldMappingFunction" />
      <MemberSignature Language="F#" Value="static member ExtractTokenAtPosition : string * int -&gt; Microsoft.Azure.Search.Models.FieldMappingFunction" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.ExtractTokenAtPosition (delimiter, position)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FieldMappingFunction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="delimiter" Type="System.String" />
        <Parameter Name="position" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="delimiter">入力文字列を分割する場合、区切り記号として使用する文字列。</param>
        <param name="position">入力文字列の分割後に取得するトークンの整数の 0 から始まる位置。</param>
        <summary>
            指定された区切り記号を使用して文字列フィールドを分割し、結果として得られる分割の指定した位置にあるトークンを取得するフィールドのマッピング関数を作成します。
            </summary>
        <returns>新しいフィールドのマッピング関数です。</returns>
        <remarks>
          <para>
            たとえば、入力がジェーン Doe の場合は、区切り記号は""(スペース) と位置が 0 の場合、結果は Jane です。位置が 1 の場合は、Doe になります。 位置が、存在しないトークンを参照する場合、エラーが返されます。
            </para>
          <para>
            ユース ケースのサンプル: PersonName フィールドが、データ ソースに含まれています、2 つの独立した FirstName と LastName フィールドとしてインデックスを作成します。 この関数を使用して、空白文字を区切り記号として使って入力を分割できます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonArrayToStringCollection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.FieldMappingFunction JsonArrayToStringCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.FieldMappingFunction JsonArrayToStringCollection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.JsonArrayToStringCollection" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function JsonArrayToStringCollection () As FieldMappingFunction" />
      <MemberSignature Language="F#" Value="static member JsonArrayToStringCollection : unit -&gt; Microsoft.Azure.Search.Models.FieldMappingFunction" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.JsonArrayToStringCollection " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FieldMappingFunction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            インデックスに Collection(Edm.String) フィールドを設定するために使用する文字列配列に文字列の JSON 配列として書式設定文字列を変換するフィールドのマッピング関数を作成します。
            </summary>
        <returns>新しいフィールドのマッピング関数です。</returns>
        <remarks>
          <para>
            たとえば、入力文字列は、["red"、"white"、"blue"]、Collection(Edm.String) の種類の対象フィールドに 3 つの値の赤、白、および青で表示されます。 JSON 文字列配列として解析できない入力値では、エラーが返されます。
            </para>
          <para>
            ユース ケースのサンプル: Azure SQL データベースは Azure Search で Collection(Edm.String) フィールドに必然的にマップされる組み込みのデータ型がありません。 文字列コレクション フィールドに値を入力するには、ソース データを JSON 文字列配列とし書式設定して、この関数を使用します。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FieldMappingFunction.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィールドのマッピング関数の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FieldMappingFunction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または関数に渡すパラメーターの名前/値ペアのディクショナリを設定します。 各値は、プリミティブ型でなければなりません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fieldMappingFunction.Validate " />
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