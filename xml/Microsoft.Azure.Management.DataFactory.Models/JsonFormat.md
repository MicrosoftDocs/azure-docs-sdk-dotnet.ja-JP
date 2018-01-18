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
            <span data-ttu-id="93a0a-101">JSON 形式で格納されているデータ。</span><span class="sxs-lookup"><span data-stu-id="93a0a-101">The data stored in JSON format.</span></span>
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
            <span data-ttu-id="93a0a-102">JsonFormat クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-102">Initializes a new instance of the JsonFormat class.</span></span>
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
        <param name="additionalProperties"><span data-ttu-id="93a0a-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="93a0a-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="serializer"><span data-ttu-id="93a0a-104">シリアライザー。</span><span class="sxs-lookup"><span data-stu-id="93a0a-104">Serializer.</span></span> <span data-ttu-id="93a0a-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="deserializer"><span data-ttu-id="93a0a-106">デシリアライザー。</span><span class="sxs-lookup"><span data-stu-id="93a0a-106">Deserializer.</span></span> <span data-ttu-id="93a0a-107">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-107">Type: string (or Expression with resultType string).</span></span></param>
        <param name="filePattern"><span data-ttu-id="93a0a-108">JSON のファイルのパターン。</span><span class="sxs-lookup"><span data-stu-id="93a0a-108">File pattern of JSON.</span></span> <span data-ttu-id="93a0a-109">JSON オブジェクトのコレクションを分割する方法をより具体的になります。</span><span class="sxs-lookup"><span data-stu-id="93a0a-109">To be more specific, the way of separating a collection of JSON objects.</span></span> <span data-ttu-id="93a0a-110">既定値は、'setOfObjects' です。</span><span class="sxs-lookup"><span data-stu-id="93a0a-110">The default value is 'setOfObjects'.</span></span> <span data-ttu-id="93a0a-111">このコマンドは、大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-111">It is case-sensitive.</span></span> <span data-ttu-id="93a0a-112">使用可能な値が含まれます: 'setOfObjects'、'arrayOfObjects'</span><span class="sxs-lookup"><span data-stu-id="93a0a-112">Possible values include: 'setOfObjects', 'arrayOfObjects'</span></span></param>
        <param name="nestingSeparator"><span data-ttu-id="93a0a-113">入れ子になったレベルを区切るために使用する文字。</span><span class="sxs-lookup"><span data-stu-id="93a0a-113">The character used to separate nesting levels.</span></span> <span data-ttu-id="93a0a-114">既定値は '.'(ドット)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-114">Default value is '.' (dot).</span></span> <span data-ttu-id="93a0a-115">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-115">Type: string (or Expression with resultType string).</span></span></param>
        <param name="encodingName"><span data-ttu-id="93a0a-116">使用するエンコーディングのコード ページ名。</span><span class="sxs-lookup"><span data-stu-id="93a0a-116">The code page name of the preferred encoding.</span></span> <span data-ttu-id="93a0a-117">指定しない場合、バイト順マーク (BOM) が別の Unicode エンコードを表しますしない限り、既定値は 'utf-8' にします。</span><span class="sxs-lookup"><span data-stu-id="93a0a-117">If not provided, the default value is 'utf-8', unless the byte order mark (BOM) denotes another Unicode encoding.</span></span> <span data-ttu-id="93a0a-118">次の参照のエンコーディングのテーブルの 'Name' 列でサポートされている値の完全な一覧が見つかりません: https://go.microsoft.com/fwlink/?linkid=861078 です。</span><span class="sxs-lookup"><span data-stu-id="93a0a-118">The full list of supported values can be found in the 'Name' column of the table of encodings in the following reference: https://go.microsoft.com/fwlink/?linkid=861078.</span></span> <span data-ttu-id="93a0a-119">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-119">Type: string (or Expression with resultType string).</span></span></param>
        <param name="jsonNodeReference"><span data-ttu-id="93a0a-120">フラット化する JSON 配列要素の JSONPath します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-120">The JSONPath of the JSON array element to be flattened.</span></span> <span data-ttu-id="93a0a-121">例:"$ です。ArrayPath"です。</span><span class="sxs-lookup"><span data-stu-id="93a0a-121">Example: "$.ArrayPath".</span></span> <span data-ttu-id="93a0a-122">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-122">Type: string (or Expression with resultType string).</span></span></param>
        <param name="jsonPathDefinition"><span data-ttu-id="93a0a-123">JSON ファイルからデータを抽出するカスタマイズされた列名を持つ各列のマッピングの JSONPath 定義します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-123">The JSONPath definition for each column mapping with a customized column name to extract data from JSON file.</span></span> <span data-ttu-id="93a0a-124">ルート オブジェクトの下のフィールドには、「$」; で開始します。jsonNodeReference プロパティが選択した配列内のフィールドには、配列の要素から開始します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-124">For fields under root object, start with "$"; for fields inside the array chosen by jsonNodeReference property, start from the array element.</span></span> <span data-ttu-id="93a0a-125">例: {"Column1":"$ です。Column1Path"、"Column2":"Column2PathInArray"}。</span><span class="sxs-lookup"><span data-stu-id="93a0a-125">Example: {"Column1": "$.Column1Path", "Column2": "Column2PathInArray"}.</span></span> <span data-ttu-id="93a0a-126">型: オブジェクト (または式 resultType オブジェクトを使用)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-126">Type: object (or Expression with resultType object).</span></span></param>
        <summary>
            <span data-ttu-id="93a0a-127">JsonFormat クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-127">Initializes a new instance of the JsonFormat class.</span></span>
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
            <span data-ttu-id="93a0a-128">取得または使用するエンコーディングのコード ページ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-128">Gets or sets the code page name of the preferred encoding.</span></span> <span data-ttu-id="93a0a-129">指定しない場合、バイト順マーク (BOM) が別の Unicode エンコードを表しますしない限り、既定値は 'utf-8' にします。</span><span class="sxs-lookup"><span data-stu-id="93a0a-129">If not provided, the default value is 'utf-8', unless the byte order mark (BOM) denotes another Unicode encoding.</span></span> <span data-ttu-id="93a0a-130">次の参照のエンコーディングのテーブルの 'Name' 列でサポートされている値の完全な一覧が見つかりません: https://go.microsoft.com/fwlink/?linkid=861078 です。</span><span class="sxs-lookup"><span data-stu-id="93a0a-130">The full list of supported values can be found in the 'Name' column of the table of encodings in the following reference: https://go.microsoft.com/fwlink/?linkid=861078.</span></span> <span data-ttu-id="93a0a-131">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-131">Type: string (or Expression with resultType string).</span></span>
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
            <span data-ttu-id="93a0a-132">取得または JSON のファイルのパターンを設定します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-132">Gets or sets file pattern of JSON.</span></span> <span data-ttu-id="93a0a-133">JSON オブジェクトのコレクションを分割する方法をより具体的になります。</span><span class="sxs-lookup"><span data-stu-id="93a0a-133">To be more specific, the way of separating a collection of JSON objects.</span></span> <span data-ttu-id="93a0a-134">既定値は、'setOfObjects' です。</span><span class="sxs-lookup"><span data-stu-id="93a0a-134">The default value is 'setOfObjects'.</span></span> <span data-ttu-id="93a0a-135">このコマンドは、大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-135">It is case-sensitive.</span></span> <span data-ttu-id="93a0a-136">使用可能な値が含まれます: 'setOfObjects'、'arrayOfObjects'</span><span class="sxs-lookup"><span data-stu-id="93a0a-136">Possible values include: 'setOfObjects', 'arrayOfObjects'</span></span>
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
            <span data-ttu-id="93a0a-137">取得またはフラット化する JSON 配列要素の JSONPath を設定します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-137">Gets or sets the JSONPath of the JSON array element to be flattened.</span></span> <span data-ttu-id="93a0a-138">例:"$ です。ArrayPath"です。</span><span class="sxs-lookup"><span data-stu-id="93a0a-138">Example: "$.ArrayPath".</span></span> <span data-ttu-id="93a0a-139">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-139">Type: string (or Expression with resultType string).</span></span>
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
            <span data-ttu-id="93a0a-140">取得または JSON ファイルからデータを抽出するカスタマイズされた列名を持つ各列のマッピングの JSONPath 定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-140">Gets or sets the JSONPath definition for each column mapping with a customized column name to extract data from JSON file.</span></span> <span data-ttu-id="93a0a-141">ルート オブジェクトの下のフィールドには、「$」; で開始します。jsonNodeReference プロパティが選択した配列内のフィールドには、配列の要素から開始します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-141">For fields under root object, start with "$"; for fields inside the array chosen by jsonNodeReference property, start from the array element.</span></span>
            <span data-ttu-id="93a0a-142">例: {"Column1":"$ です。Column1Path"、"Column2":"Column2PathInArray"}。</span><span class="sxs-lookup"><span data-stu-id="93a0a-142">Example: {"Column1": "$.Column1Path", "Column2": "Column2PathInArray"}.</span></span> <span data-ttu-id="93a0a-143">型: オブジェクト (または式 resultType オブジェクトを使用)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-143">Type: object (or Expression with resultType object).</span></span>
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
            <span data-ttu-id="93a0a-144">取得または入れ子になったレベルを区切るために使用する文字を設定します。</span><span class="sxs-lookup"><span data-stu-id="93a0a-144">Gets or sets the character used to separate nesting levels.</span></span> <span data-ttu-id="93a0a-145">既定値は '.'(ドット)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-145">Default value is '.' (dot).</span></span> <span data-ttu-id="93a0a-146">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="93a0a-146">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>