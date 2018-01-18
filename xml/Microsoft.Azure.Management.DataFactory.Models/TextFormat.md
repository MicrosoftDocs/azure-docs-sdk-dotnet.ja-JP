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
            <span data-ttu-id="fed99-101">テキスト形式で格納されているデータ。</span><span class="sxs-lookup"><span data-stu-id="fed99-101">The data stored in text format.</span></span>
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
            <span data-ttu-id="fed99-102">TextFormat クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fed99-102">Initializes a new instance of the TextFormat class.</span></span>
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
        <param name="additionalProperties"><span data-ttu-id="fed99-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="fed99-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="serializer"><span data-ttu-id="fed99-104">シリアライザー。</span><span class="sxs-lookup"><span data-stu-id="fed99-104">Serializer.</span></span> <span data-ttu-id="fed99-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="deserializer"><span data-ttu-id="fed99-106">デシリアライザー。</span><span class="sxs-lookup"><span data-stu-id="fed99-106">Deserializer.</span></span> <span data-ttu-id="fed99-107">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-107">Type: string (or Expression with resultType string).</span></span></param>
        <param name="columnDelimiter"><span data-ttu-id="fed99-108">列の区切り記号。</span><span class="sxs-lookup"><span data-stu-id="fed99-108">The column delimiter.</span></span> <span data-ttu-id="fed99-109">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-109">Type: string (or Expression with resultType string).</span></span></param>
        <param name="rowDelimiter"><span data-ttu-id="fed99-110">行区切り記号です。</span><span class="sxs-lookup"><span data-stu-id="fed99-110">The row delimiter.</span></span> <span data-ttu-id="fed99-111">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-111">Type: string (or Expression with resultType string).</span></span></param>
        <param name="escapeChar"><span data-ttu-id="fed99-112">エスケープ文字。</span><span class="sxs-lookup"><span data-stu-id="fed99-112">The escape character.</span></span> <span data-ttu-id="fed99-113">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-113">Type: string (or Expression with resultType string).</span></span></param>
        <param name="quoteChar"><span data-ttu-id="fed99-114">引用符文字。</span><span class="sxs-lookup"><span data-stu-id="fed99-114">The quote character.</span></span> <span data-ttu-id="fed99-115">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-115">Type: string (or Expression with resultType string).</span></span></param>
        <param name="nullValue"><span data-ttu-id="fed99-116">Null 値の文字列。</span><span class="sxs-lookup"><span data-stu-id="fed99-116">The null value string.</span></span> <span data-ttu-id="fed99-117">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-117">Type: string (or Expression with resultType string).</span></span></param>
        <param name="encodingName"><span data-ttu-id="fed99-118">使用するエンコーディングのコード ページ名。</span><span class="sxs-lookup"><span data-stu-id="fed99-118">The code page name of the preferred encoding.</span></span> <span data-ttu-id="fed99-119">かどうかミス、既定値は ΓÇ £utf 8ΓÇ ¥ 限り BOM は、Unicode、別のエンコードを表します。</span><span class="sxs-lookup"><span data-stu-id="fed99-119">If miss, the default value is ΓÇ£utf-8ΓÇ¥, unless BOM denotes another Unicode encoding.</span></span> <span data-ttu-id="fed99-120">サポートされている値を設定する次のリンク内のテーブルの ΓÇ £NameΓÇ ¥ 列を参照してください: https://msdn.microsoft.com/library/system.text.encoding.aspx です。</span><span class="sxs-lookup"><span data-stu-id="fed99-120">Refer to the ΓÇ£NameΓÇ¥ column of the table in the following link to set supported values: https://msdn.microsoft.com/library/system.text.encoding.aspx.</span></span> <span data-ttu-id="fed99-121">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-121">Type: string (or Expression with resultType string).</span></span></param>
        <param name="treatEmptyAsNull"><span data-ttu-id="fed99-122">テキスト ファイルに空の列の値を null として扱います。</span><span class="sxs-lookup"><span data-stu-id="fed99-122">Treat empty column values in the text file as null.</span></span> <span data-ttu-id="fed99-123">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="fed99-123">The default value is true.</span></span> <span data-ttu-id="fed99-124">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="fed99-124">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <param name="skipLineCount"><span data-ttu-id="fed99-125">テキスト ファイルの解析中にスキップするには、行/行の数。</span><span class="sxs-lookup"><span data-stu-id="fed99-125">The number of lines/rows to be skipped when parsing text files.</span></span> <span data-ttu-id="fed99-126">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="fed99-126">The default value is 0.</span></span> <span data-ttu-id="fed99-127">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="fed99-127">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="firstRowAsHeader"><span data-ttu-id="fed99-128">入力として使用する場合は、データの最初の行をヘッダーとして扱います。</span><span class="sxs-lookup"><span data-stu-id="fed99-128">When used as input, treat the first row of data as headers.</span></span> <span data-ttu-id="fed99-129">出力として使用する場合は、データの最初の行として出力に、ヘッダーを書き込みます。</span><span class="sxs-lookup"><span data-stu-id="fed99-129">When used as output,write the headers into the output as the first row of data.</span></span> <span data-ttu-id="fed99-130">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="fed99-130">The default value is false.</span></span>
            <span data-ttu-id="fed99-131">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="fed99-131">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <summary>
            <span data-ttu-id="fed99-132">TextFormat クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fed99-132">Initializes a new instance of the TextFormat class.</span></span>
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
            <span data-ttu-id="fed99-133">取得または列の区切り記号を設定します。</span><span class="sxs-lookup"><span data-stu-id="fed99-133">Gets or sets the column delimiter.</span></span> <span data-ttu-id="fed99-134">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-134">Type: string (or Expression with resultType string).</span></span>
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
            <span data-ttu-id="fed99-135">取得または使用するエンコーディングのコード ページ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="fed99-135">Gets or sets the code page name of the preferred encoding.</span></span> <span data-ttu-id="fed99-136">かどうかミス、既定値は ΓÇ £utf 8ΓÇ ¥ 限り BOM は、Unicode、別のエンコードを表します。</span><span class="sxs-lookup"><span data-stu-id="fed99-136">If miss, the default value is ΓÇ£utf-8ΓÇ¥, unless BOM denotes another Unicode encoding.</span></span> <span data-ttu-id="fed99-137">サポートされている値を設定する次のリンク内のテーブルの ΓÇ £NameΓÇ ¥ 列を参照してください: https://msdn.microsoft.com/library/system.text.encoding.aspx です。</span><span class="sxs-lookup"><span data-stu-id="fed99-137">Refer to the ΓÇ£NameΓÇ¥ column of the table in the following link to set supported values: https://msdn.microsoft.com/library/system.text.encoding.aspx.</span></span> <span data-ttu-id="fed99-138">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-138">Type: string (or Expression with resultType string).</span></span>
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
            <span data-ttu-id="fed99-139">取得またはエスケープ文字を設定します。</span><span class="sxs-lookup"><span data-stu-id="fed99-139">Gets or sets the escape character.</span></span> <span data-ttu-id="fed99-140">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-140">Type: string (or Expression with resultType string).</span></span>
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
            <span data-ttu-id="fed99-141">取得または設定として入力、扱うデータの最初の行ヘッダーとして使用する場合。</span><span class="sxs-lookup"><span data-stu-id="fed99-141">Gets or sets when used as input, treat the first row of data as headers.</span></span> <span data-ttu-id="fed99-142">出力として使用する場合は、データの最初の行として出力に、ヘッダーを書き込みます。</span><span class="sxs-lookup"><span data-stu-id="fed99-142">When used as output,write the headers into the output as the first row of data.</span></span> <span data-ttu-id="fed99-143">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="fed99-143">The default value is false.</span></span> <span data-ttu-id="fed99-144">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="fed99-144">Type: boolean (or Expression with resultType boolean).</span></span>
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
            <span data-ttu-id="fed99-145">取得または null 値の文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="fed99-145">Gets or sets the null value string.</span></span> <span data-ttu-id="fed99-146">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-146">Type: string (or Expression with resultType string).</span></span>
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
            <span data-ttu-id="fed99-147">取得または引用文字を設定します。</span><span class="sxs-lookup"><span data-stu-id="fed99-147">Gets or sets the quote character.</span></span> <span data-ttu-id="fed99-148">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-148">Type: string (or Expression with resultType string).</span></span>
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
            <span data-ttu-id="fed99-149">取得または行区切り記号を設定します。</span><span class="sxs-lookup"><span data-stu-id="fed99-149">Gets or sets the row delimiter.</span></span> <span data-ttu-id="fed99-150">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fed99-150">Type: string (or Expression with resultType string).</span></span>
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
            <span data-ttu-id="fed99-151">取得またはテキスト ファイルの解析中にスキップするには、行/行の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="fed99-151">Gets or sets the number of lines/rows to be skipped when parsing text files.</span></span> <span data-ttu-id="fed99-152">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="fed99-152">The default value is 0.</span></span> <span data-ttu-id="fed99-153">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="fed99-153">Type: integer (or Expression with resultType integer).</span></span>
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
            <span data-ttu-id="fed99-154">取得または設定は、テキスト ファイルに空の列の値を null として扱います。</span><span class="sxs-lookup"><span data-stu-id="fed99-154">Gets or sets treat empty column values in the text file as null.</span></span>
            <span data-ttu-id="fed99-155">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="fed99-155">The default value is true.</span></span> <span data-ttu-id="fed99-156">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="fed99-156">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>