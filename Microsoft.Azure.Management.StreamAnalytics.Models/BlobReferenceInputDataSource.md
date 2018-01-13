<Type Name="BlobReferenceInputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource">
  <TypeSignature Language="C#" Value="public class BlobReferenceInputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobReferenceInputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobReferenceInputDataSource&#xA;Inherits ReferenceInputDataSource" />
  <TypeSignature Language="F#" Value="type BlobReferenceInputDataSource = class&#xA;    inherit ReferenceInputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.ReferenceInputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Storage/Blob")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="95223-101">参照データを含む blob 入力データ ソースについて説明します。</span><span class="sxs-lookup"><span data-stu-id="95223-101">Describes a blob input data source that contains reference data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobReferenceInputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="95223-102">BlobReferenceInputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="95223-102">Initializes a new instance of the BlobReferenceInputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobReferenceInputDataSource (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts = null, string container = null, string pathPattern = null, string dateFormat = null, string timeFormat = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts, string container, string pathPattern, string dateFormat, string timeFormat) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageAccounts As IList(Of StorageAccount) = null, Optional container As String = null, Optional pathPattern As String = null, Optional dateFormat As String = null, Optional timeFormat As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource (storageAccounts, container, pathPattern, dateFormat, timeFormat)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt;" />
        <Parameter Name="container" Type="System.String" />
        <Parameter Name="pathPattern" Type="System.String" />
        <Parameter Name="dateFormat" Type="System.String" />
        <Parameter Name="timeFormat" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccounts"><span data-ttu-id="95223-103">1 つまたは複数の Azure ストレージ アカウントの一覧。</span><span class="sxs-lookup"><span data-stu-id="95223-103">A list of one or more Azure Storage accounts.</span></span> <span data-ttu-id="95223-104">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="95223-104">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="container"><span data-ttu-id="95223-105">関連付けられたストレージ アカウント内のコンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="95223-105">The name of a container within the associated Storage account.</span></span> <span data-ttu-id="95223-106">このコンテナーからの読み取りまたはに書き込まれる blob が含まれています。</span><span class="sxs-lookup"><span data-stu-id="95223-106">This container contains either the blob(s) to be read from or written to.</span></span> <span data-ttu-id="95223-107">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="95223-107">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="pathPattern"><span data-ttu-id="95223-108">Blob パスのパターン。</span><span class="sxs-lookup"><span data-stu-id="95223-108">The blob path pattern.</span></span> <span data-ttu-id="95223-109">正規表現ではありません。</span><span class="sxs-lookup"><span data-stu-id="95223-109">Not a regular expression.</span></span> <span data-ttu-id="95223-110">決定するかどうかが含まれるジョブに入力または出力として、名前を照合する blob に対してパターンを表します。</span><span class="sxs-lookup"><span data-stu-id="95223-110">It represents a pattern against which blob names will be matched to determine whether or not they should be included as input or output to the job.</span></span> <span data-ttu-id="95223-111">Https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input または https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output より詳細な説明と例についてを参照してください。</span><span class="sxs-lookup"><span data-stu-id="95223-111">See https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input or https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for a more detailed explanation and example.</span></span></param>
        <param name="dateFormat"><span data-ttu-id="95223-112">日付形式です。</span><span class="sxs-lookup"><span data-stu-id="95223-112">The date format.</span></span> <span data-ttu-id="95223-113">PathPattern に {date} が表示されたら、場所にこのプロパティの値が代わりに日付形式として使用します。</span><span class="sxs-lookup"><span data-stu-id="95223-113">Wherever {date} appears in pathPattern, the value of this property is used as the date format instead.</span></span></param>
        <param name="timeFormat"><span data-ttu-id="95223-114">時刻の形式。</span><span class="sxs-lookup"><span data-stu-id="95223-114">The time format.</span></span> <span data-ttu-id="95223-115">PathPattern に {date} が表示されたら、場所にこのプロパティの値が代わりに、時間形式として使用します。</span><span class="sxs-lookup"><span data-stu-id="95223-115">Wherever {time} appears in pathPattern, the value of this property is used as the time format instead.</span></span></param>
        <summary>
            <span data-ttu-id="95223-116">BlobReferenceInputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="95223-116">Initializes a new instance of the BlobReferenceInputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public string Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As String" />
      <MemberSignature Language="F#" Value="member this.Container : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95223-117">取得または関連付けられたストレージ アカウント内のコンテナーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="95223-117">Gets or sets the name of a container within the associated Storage account.</span></span> <span data-ttu-id="95223-118">このコンテナーからの読み取りまたはに書き込まれる blob が含まれています。</span><span class="sxs-lookup"><span data-stu-id="95223-118">This container contains either the blob(s) to be read from or written to.</span></span> <span data-ttu-id="95223-119">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="95223-119">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateFormat">
      <MemberSignature Language="C#" Value="public string DateFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.DateFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property DateFormat As String" />
      <MemberSignature Language="F#" Value="member this.DateFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.DateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dateFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95223-120">取得または日付の書式を設定します。</span><span class="sxs-lookup"><span data-stu-id="95223-120">Gets or sets the date format.</span></span> <span data-ttu-id="95223-121">PathPattern に {date} が表示されたら、場所にこのプロパティの値が代わりに日付形式として使用します。</span><span class="sxs-lookup"><span data-stu-id="95223-121">Wherever {date} appears in pathPattern, the value of this property is used as the date format instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathPattern">
      <MemberSignature Language="C#" Value="public string PathPattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathPattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.PathPattern" />
      <MemberSignature Language="VB.NET" Value="Public Property PathPattern As String" />
      <MemberSignature Language="F#" Value="member this.PathPattern : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.PathPattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pathPattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95223-122">取得または blob パス パターンを設定します。</span><span class="sxs-lookup"><span data-stu-id="95223-122">Gets or sets the blob path pattern.</span></span> <span data-ttu-id="95223-123">正規表現ではありません。</span><span class="sxs-lookup"><span data-stu-id="95223-123">Not a regular expression.</span></span> <span data-ttu-id="95223-124">決定するかどうかが含まれるジョブに入力または出力として、名前を照合する blob に対してパターンを表します。</span><span class="sxs-lookup"><span data-stu-id="95223-124">It represents a pattern against which blob names will be matched to determine whether or not they should be included as input or output to the job.</span></span> <span data-ttu-id="95223-125">Https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input または https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output より詳細な説明と例についてを参照してください。</span><span class="sxs-lookup"><span data-stu-id="95223-125">See https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input or https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for a more detailed explanation and example.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccounts As IList(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95223-126">取得または 1 つまたは複数の Azure ストレージ アカウントの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="95223-126">Gets or sets a list of one or more Azure Storage accounts.</span></span> <span data-ttu-id="95223-127">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="95223-127">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeFormat">
      <MemberSignature Language="C#" Value="public string TimeFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.TimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeFormat As String" />
      <MemberSignature Language="F#" Value="member this.TimeFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobReferenceInputDataSource.TimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95223-128">取得または時刻の形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="95223-128">Gets or sets the time format.</span></span> <span data-ttu-id="95223-129">PathPattern に {date} が表示されたら、場所にこのプロパティの値が代わりに、時間形式として使用します。</span><span class="sxs-lookup"><span data-stu-id="95223-129">Wherever {time} appears in pathPattern, the value of this property is used as the time format instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>