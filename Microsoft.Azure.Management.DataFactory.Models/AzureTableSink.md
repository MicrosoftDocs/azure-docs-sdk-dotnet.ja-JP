<Type Name="AzureTableSink" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink">
  <TypeSignature Language="C#" Value="public class AzureTableSink : Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureTableSink extends Microsoft.Azure.Management.DataFactory.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureTableSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type AzureTableSink = class&#xA;    inherit CopySink" />
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
            <span data-ttu-id="a42ac-101">コピー アクティビティの Azure テーブル シンクです。</span><span class="sxs-lookup"><span data-stu-id="a42ac-101">A copy activity Azure Table sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.#ctor" />
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
            <span data-ttu-id="a42ac-102">AzureTableSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a42ac-102">Initializes a new instance of the AzureTableSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSink (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object writeBatchSize = null, object writeBatchTimeout = null, object sinkRetryCount = null, object sinkRetryWait = null, object azureTableDefaultPartitionKeyValue = null, object azureTablePartitionKeyName = null, object azureTableRowKeyName = null, object azureTableInsertType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object writeBatchSize, object writeBatchTimeout, object sinkRetryCount, object sinkRetryWait, object azureTableDefaultPartitionKeyValue, object azureTablePartitionKeyName, object azureTableRowKeyName, object azureTableInsertType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional writeBatchSize As Object = null, Optional writeBatchTimeout As Object = null, Optional sinkRetryCount As Object = null, Optional sinkRetryWait As Object = null, Optional azureTableDefaultPartitionKeyValue As Object = null, Optional azureTablePartitionKeyName As Object = null, Optional azureTableRowKeyName As Object = null, Optional azureTableInsertType As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureTableSink : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureTableSink" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureTableSink (additionalProperties, writeBatchSize, writeBatchTimeout, sinkRetryCount, sinkRetryWait, azureTableDefaultPartitionKeyValue, azureTablePartitionKeyName, azureTableRowKeyName, azureTableInsertType)" />
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
        <Parameter Name="azureTableDefaultPartitionKeyValue" Type="System.Object" />
        <Parameter Name="azureTablePartitionKeyName" Type="System.Object" />
        <Parameter Name="azureTableRowKeyName" Type="System.Object" />
        <Parameter Name="azureTableInsertType" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="a42ac-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="a42ac-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="writeBatchSize"><span data-ttu-id="a42ac-104">バッチ サイズを記述します。</span><span class="sxs-lookup"><span data-stu-id="a42ac-104">Write batch size.</span></span> <span data-ttu-id="a42ac-105">型: 整数 (または式と resultType 整数)、最小値: 0。</span><span class="sxs-lookup"><span data-stu-id="a42ac-105">Type: integer (or Expression with resultType integer), minimum: 0.</span></span></param>
        <param name="writeBatchTimeout"><span data-ttu-id="a42ac-106">バッチ タイムアウトを記述します。</span><span class="sxs-lookup"><span data-stu-id="a42ac-106">Write batch timeout.</span></span> <span data-ttu-id="a42ac-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="a42ac-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="sinkRetryCount"><span data-ttu-id="a42ac-108">再試行回数をシンクします。</span><span class="sxs-lookup"><span data-stu-id="a42ac-108">Sink retry count.</span></span> <span data-ttu-id="a42ac-109">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="a42ac-109">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sinkRetryWait"><span data-ttu-id="a42ac-110">再試行の待機をシンクします。</span><span class="sxs-lookup"><span data-stu-id="a42ac-110">Sink retry wait.</span></span> <span data-ttu-id="a42ac-111">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="a42ac-111">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="azureTableDefaultPartitionKeyValue"><span data-ttu-id="a42ac-112">Azure テーブル既定のパーティション キー値。</span><span class="sxs-lookup"><span data-stu-id="a42ac-112">Azure Table default partition key value.</span></span> <span data-ttu-id="a42ac-113">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="a42ac-113">Type: string (or Expression with resultType string).</span></span></param>
        <param name="azureTablePartitionKeyName"><span data-ttu-id="a42ac-114">Azure テーブルのパーティション キーの名前。</span><span class="sxs-lookup"><span data-stu-id="a42ac-114">Azure Table partition key name.</span></span> <span data-ttu-id="a42ac-115">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="a42ac-115">Type: string (or Expression with resultType string).</span></span></param>
        <param name="azureTableRowKeyName"><span data-ttu-id="a42ac-116">Azure テーブルの行キーの名前。</span><span class="sxs-lookup"><span data-stu-id="a42ac-116">Azure Table row key name.</span></span> <span data-ttu-id="a42ac-117">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="a42ac-117">Type: string (or Expression with resultType string).</span></span></param>
        <param name="azureTableInsertType"><span data-ttu-id="a42ac-118">Azure テーブルは、型を挿入します。</span><span class="sxs-lookup"><span data-stu-id="a42ac-118">Azure Table insert type.</span></span> <span data-ttu-id="a42ac-119">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="a42ac-119">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="a42ac-120">AzureTableSink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a42ac-120">Initializes a new instance of the AzureTableSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableDefaultPartitionKeyValue">
      <MemberSignature Language="C#" Value="public object AzureTableDefaultPartitionKeyValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableDefaultPartitionKeyValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableDefaultPartitionKeyValue" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableDefaultPartitionKeyValue As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableDefaultPartitionKeyValue : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableDefaultPartitionKeyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableDefaultPartitionKeyValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a42ac-121">取得または azure テーブル既定のパーティション キー値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a42ac-121">Gets or sets azure Table default partition key value.</span></span> <span data-ttu-id="a42ac-122">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="a42ac-122">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableInsertType">
      <MemberSignature Language="C#" Value="public object AzureTableInsertType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableInsertType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableInsertType" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableInsertType As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableInsertType : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableInsertType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableInsertType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a42ac-123">取得または azure テーブルの挿入の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="a42ac-123">Gets or sets azure Table insert type.</span></span> <span data-ttu-id="a42ac-124">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="a42ac-124">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTablePartitionKeyName">
      <MemberSignature Language="C#" Value="public object AzureTablePartitionKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTablePartitionKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTablePartitionKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTablePartitionKeyName As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTablePartitionKeyName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTablePartitionKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTablePartitionKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a42ac-125">取得または azure のテーブルのパーティション キーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a42ac-125">Gets or sets azure Table partition key name.</span></span> <span data-ttu-id="a42ac-126">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="a42ac-126">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableRowKeyName">
      <MemberSignature Language="C#" Value="public object AzureTableRowKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object AzureTableRowKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableRowKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableRowKeyName As Object" />
      <MemberSignature Language="F#" Value="member this.AzureTableRowKeyName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureTableSink.AzureTableRowKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureTableRowKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a42ac-127">取得または azure のテーブル行のキー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="a42ac-127">Gets or sets azure Table row key name.</span></span> <span data-ttu-id="a42ac-128">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="a42ac-128">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>