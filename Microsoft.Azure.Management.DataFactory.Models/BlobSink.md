<Type Name="BlobSink" FullName="Microsoft.Azure.Management.DataFactory.Models.BlobSink">
  <TypeSignature Language="C#" Value="public class BlobSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.BlobSink" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type BlobSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="994db-101">コピー アクティビティの Azure Blob シンクです。</span><span class="sxs-lookup"><span data-stu-id="994db-101">A copy activity Azure Blob sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobSink.#ctor" />
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
            <span data-ttu-id="994db-102">BlobSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="994db-102">Initializes a new instance of the BlobSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, object blobWriterOverwriteFiles = null, object blobWriterDateTimeFormat = null, object blobWriterAddHeader = null, string copyBehavior = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, object blobWriterOverwriteFiles, object blobWriterDateTimeFormat, object blobWriterAddHeader, string copyBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.BlobSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional blobWriterOverwriteFiles As Object = null, Optional blobWriterDateTimeFormat As Object = null, Optional blobWriterAddHeader As Object = null, Optional copyBehavior As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.BlobSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj * obj * obj * string -&gt; Microsoft.Azure.Management.DataFactory.Models.BlobSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.BlobSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, blobWriterOverwriteFiles, blobWriterDateTimeFormat, blobWriterAddHeader, copyBehavior)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="writeBatchSize" Type="System.Object" />
        <Parameter Name="writeBatchTimeout" Type="System.Object" />
        <Parameter Name="sinkRetryCount" Type="System.Object" />
        <Parameter Name="sinkRetryWait" Type="System.Object" />
        <Parameter Name="blobWriterOverwriteFiles" Type="System.Object" />
        <Parameter Name="blobWriterDateTimeFormat" Type="System.Object" />
        <Parameter Name="blobWriterAddHeader" Type="System.Object" />
        <Parameter Name="copyBehavior" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="994db-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="994db-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="writeBatchSize"><span data-ttu-id="994db-104">バッチ サイズを記述します。</span><span class="sxs-lookup"><span data-stu-id="994db-104">Write batch size.</span></span> <span data-ttu-id="994db-105">型: 整数 (または式と resultType 整数)、最小値: 0。</span><span class="sxs-lookup"><span data-stu-id="994db-105">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="writeBatchTimeout"><span data-ttu-id="994db-106">バッチ タイムアウトを記述します。</span><span class="sxs-lookup"><span data-stu-id="994db-106">Write batch timeout.</span></span> <span data-ttu-id="994db-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="994db-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sinkRetryCount"><span data-ttu-id="994db-108">再試行回数をシンクします。</span><span class="sxs-lookup"><span data-stu-id="994db-108">Sink retry count.</span></span> <span data-ttu-id="994db-109">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="994db-109">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sinkRetryWait"><span data-ttu-id="994db-110">再試行の待機をシンクします。</span><span class="sxs-lookup"><span data-stu-id="994db-110">Sink retry wait.</span></span> <span data-ttu-id="994db-111">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="994db-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="blobWriterOverwriteFiles"><span data-ttu-id="994db-112">Blob のライター ファイルを上書きします。</span><span class="sxs-lookup"><span data-stu-id="994db-112">Blob writer overwrite files.</span></span>
            <span data-ttu-id="994db-113">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="994db-113">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <param name="blobWriterDateTimeFormat"><span data-ttu-id="994db-114">Blob ライター日付/時刻形式。</span><span class="sxs-lookup"><span data-stu-id="994db-114">Blob writer date time format.</span></span> <span data-ttu-id="994db-115">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="994db-115">Type: string (or Expression with resultType string).</span></span></param>
        <param name="blobWriterAddHeader"><span data-ttu-id="994db-116">Blob のライターでは、ヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="994db-116">Blob writer add header.</span></span> <span data-ttu-id="994db-117">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="994db-117">Type: boolean (or Expression with resultType boolean).</span></span></param>
        <param name="copyBehavior"><span data-ttu-id="994db-118">コピー シンクのコピー動作の型。</span><span class="sxs-lookup"><span data-stu-id="994db-118">The type of copy behavior for copy sink.</span></span>
            <span data-ttu-id="994db-119">使用可能な値が含まれます: 'PreserveHierarchy'、'FlattenHierarchy'、'MergeFiles'</span><span class="sxs-lookup"><span data-stu-id="994db-119">Possible values include: 'PreserveHierarchy', 'FlattenHierarchy', 'MergeFiles'</span></span></param>
        <summary>
            <span data-ttu-id="994db-120">BlobSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="994db-120">Initializes a new instance of the BlobSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobWriterAddHeader">
      <MemberSignature Language="C#" Value="public object BlobWriterAddHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object BlobWriterAddHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterAddHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobWriterAddHeader As Object" />
      <MemberSignature Language="F#" Value="member this.BlobWriterAddHeader : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterAddHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobWriterAddHeader")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="994db-121">Blob のライターの設定を取得またはヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="994db-121">Gets or sets blob writer add header.</span></span> <span data-ttu-id="994db-122">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="994db-122">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobWriterDateTimeFormat">
      <MemberSignature Language="C#" Value="public object BlobWriterDateTimeFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object BlobWriterDateTimeFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterDateTimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobWriterDateTimeFormat As Object" />
      <MemberSignature Language="F#" Value="member this.BlobWriterDateTimeFormat : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterDateTimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobWriterDateTimeFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="994db-123">取得または blob ライター日付/時刻形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="994db-123">Gets or sets blob writer date time format.</span></span> <span data-ttu-id="994db-124">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="994db-124">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobWriterOverwriteFiles">
      <MemberSignature Language="C#" Value="public object BlobWriterOverwriteFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object BlobWriterOverwriteFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterOverwriteFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobWriterOverwriteFiles As Object" />
      <MemberSignature Language="F#" Value="member this.BlobWriterOverwriteFiles : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSink.BlobWriterOverwriteFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobWriterOverwriteFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="994db-125">取得またはライターがファイルを上書きする blob を設定します。</span><span class="sxs-lookup"><span data-stu-id="994db-125">Gets or sets blob writer overwrite files.</span></span> <span data-ttu-id="994db-126">型: ブール値 (または式の resultType ブール値)。</span><span class="sxs-lookup"><span data-stu-id="994db-126">Type: boolean (or Expression with resultType boolean).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyBehavior">
      <MemberSignature Language="C#" Value="public string CopyBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CopyBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.BlobSink.CopyBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property CopyBehavior As String" />
      <MemberSignature Language="F#" Value="member this.CopyBehavior : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.BlobSink.CopyBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="copyBehavior")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="994db-127">取得またはコピー シンクのコピー動作の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="994db-127">Gets or sets the type of copy behavior for copy sink.</span></span> <span data-ttu-id="994db-128">使用可能な値が含まれます: 'PreserveHierarchy'、'FlattenHierarchy'、'MergeFiles'</span><span class="sxs-lookup"><span data-stu-id="994db-128">Possible values include: 'PreserveHierarchy', 'FlattenHierarchy', 'MergeFiles'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>