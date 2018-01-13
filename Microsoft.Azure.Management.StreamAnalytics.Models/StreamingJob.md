<Type Name="StreamingJob" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob">
  <TypeSignature Language="C#" Value="public class StreamingJob : Microsoft.Azure.Management.StreamAnalytics.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StreamingJob extends Microsoft.Azure.Management.StreamAnalytics.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
  <TypeSignature Language="VB.NET" Value="Public Class StreamingJob&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type StreamingJob = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="07ce0-101">Streamng ジョブ オブジェクトを名前付きのストリーミング ジョブに関連付けられているすべての情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-101">A streamng job object, containing all information associated with the named streaming job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StreamingJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-102">StreamingJob クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-102">Initializes a new instance of the StreamingJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StreamingJob (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.StreamAnalytics.Models.Sku sku = null, string jobId = null, string provisioningState = null, string jobState = null, string outputStartMode = null, Nullable&lt;DateTime&gt; outputStartTime = null, Nullable&lt;DateTime&gt; lastOutputEventTime = null, string eventsOutOfOrderPolicy = null, string outputErrorPolicy = null, Nullable&lt;int&gt; eventsOutOfOrderMaxDelayInSeconds = null, Nullable&lt;int&gt; eventsLateArrivalMaxDelayInSeconds = null, string dataLocale = null, string compatibilityLevel = null, Nullable&lt;DateTime&gt; createdDate = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; inputs = null, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; outputs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; functions = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.StreamAnalytics.Models.Sku sku, string jobId, string provisioningState, string jobState, string outputStartMode, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; outputStartTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastOutputEventTime, string eventsOutOfOrderPolicy, string outputErrorPolicy, valuetype System.Nullable`1&lt;int32&gt; eventsOutOfOrderMaxDelayInSeconds, valuetype System.Nullable`1&lt;int32&gt; eventsLateArrivalMaxDelayInSeconds, string dataLocale, string compatibilityLevel, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdDate, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; inputs, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; outputs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; functions, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.StreamAnalytics.Models.Sku,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.DateTime},System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.Input},Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.Output},System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.Function},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.StreamAnalytics.Models.Sku * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * Nullable&lt;DateTime&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob (id, name, type, location, tags, sku, jobId, provisioningState, jobState, outputStartMode, outputStartTime, lastOutputEventTime, eventsOutOfOrderPolicy, outputErrorPolicy, eventsOutOfOrderMaxDelayInSeconds, eventsLateArrivalMaxDelayInSeconds, dataLocale, compatibilityLevel, createdDate, inputs, transformation, outputs, functions, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Sku" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="jobState" Type="System.String" />
        <Parameter Name="outputStartMode" Type="System.String" />
        <Parameter Name="outputStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastOutputEventTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="eventsOutOfOrderPolicy" Type="System.String" />
        <Parameter Name="outputErrorPolicy" Type="System.String" />
        <Parameter Name="eventsOutOfOrderMaxDelayInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="eventsLateArrivalMaxDelayInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dataLocale" Type="System.String" />
        <Parameter Name="compatibilityLevel" Type="System.String" />
        <Parameter Name="createdDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="inputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="outputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" />
        <Parameter Name="functions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="07ce0-103">リソース Id</span><span class="sxs-lookup"><span data-stu-id="07ce0-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="07ce0-104">リソース名</span><span class="sxs-lookup"><span data-stu-id="07ce0-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="07ce0-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="07ce0-105">Resource type</span></span></param>
        <param name="location"><span data-ttu-id="07ce0-106">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="07ce0-106">Resource location.</span></span> <span data-ttu-id="07ce0-107">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-107">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="tags"><span data-ttu-id="07ce0-108">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="07ce0-108">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="07ce0-109">ストリーミング ジョブの SKU をについて説明します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-109">Describes the SKU of the streaming job.</span></span> <span data-ttu-id="07ce0-110">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-110">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="jobId"><span data-ttu-id="07ce0-111">ストリーミング ジョブを一意に識別する GUID です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-111">A GUID uniquely identifying the streaming job.</span></span>
            <span data-ttu-id="07ce0-112">この GUID は、ストリーミング ジョブの作成時に生成されます。</span><span class="sxs-lookup"><span data-stu-id="07ce0-112">This GUID is generated upon creation of the streaming job.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="07ce0-113">ストリーミング ジョブのプロビジョニング状態を説明します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-113">Describes the provisioning status of the streaming job.</span></span></param>
        <param name="jobState"><span data-ttu-id="07ce0-114">ストリーミング ジョブの状態を説明します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-114">Describes the state of the streaming job.</span></span></param>
        <param name="outputStartMode"><span data-ttu-id="07ce0-115">このプロパティは、作成時に、ジョブをすぐに開始することが必要な場合にのみ使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-115">This property should only be utilized when it is desired that the job be started immediately upon creation.</span></span> <span data-ttu-id="07ce0-116">値は JobStartTime、CustomTime、または lastoutputeventtime ですジョブを起動するたびに、出力イベント ストリームの開始位置を開始する必要がありますかどうかを示すためにあります outputStartTime プロパティを介して指定されたカスタム ユーザー タイムスタンプで開始 またはから開始します。最後のイベントは、時間を出力します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-116">Value may be JobStartTime, CustomTime, or LastOutputEventTime to indicate whether the starting point of the output event stream should start whenever the job is started, start at a custom user time stamp specified via the outputStartTime property, or start from the last event output time.</span></span> <span data-ttu-id="07ce0-117">使用可能な値が含まれます: 'JobStartTime'、'CustomTime'、'LastOutputEventTime'</span><span class="sxs-lookup"><span data-stu-id="07ce0-117">Possible values include: 'JobStartTime', 'CustomTime', 'LastOutputEventTime'</span></span></param>
        <param name="outputStartTime"><span data-ttu-id="07ce0-118">値がいずれか、ISO 8601 形式のタイムスタンプを出力イベント ストリームの開始位置を示すか、出力イベント ストリームが開始されていることを示す null をするたびに、ストリーミング ジョブが開始します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-118">Value is either an ISO-8601 formatted time stamp that indicates the starting point of the output event stream, or null to indicate that the output event stream will start whenever the streaming job is started.</span></span> <span data-ttu-id="07ce0-119">このプロパティは、outputStartMode が CustomTime に設定されている場合、値にすることが必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-119">This property must have a value if outputStartMode is set to CustomTime.</span></span></param>
        <param name="lastOutputEventTime"><span data-ttu-id="07ce0-120">値は、ストリーミング ジョブや、出力いないまだ生成されていることを示す null の最後の出力イベントの時刻を示すか、ISO 8601 フォーマットされたタイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="07ce0-120">Value is either an ISO-8601 formatted timestamp indicating the last output event time of the streaming job or null indicating that output has not yet been produced.</span></span> <span data-ttu-id="07ce0-121">複数の出力または複数のストリームでは、そのセットに最新の値を示します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-121">In case of multiple outputs or multiple streams, this shows the latest value in that set.</span></span></param>
        <param name="eventsOutOfOrderPolicy"><span data-ttu-id="07ce0-122">入力イベント ストリームで順序どおりに到着したイベントに適用するポリシーを示します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-122">Indicates the policy to apply to events that arrive out of order in the input event stream.</span></span>
            <span data-ttu-id="07ce0-123">使用可能な値が含まれます: '調整'、'Drop'</span><span class="sxs-lookup"><span data-stu-id="07ce0-123">Possible values include: 'Adjust', 'Drop'</span></span></param>
        <param name="outputErrorPolicy"><span data-ttu-id="07ce0-124">出力に送られてくるし、外部ストレージことによって形式が正しくありません (不足している列の値、無効な型やサイズの列の値) に書き込むことはできませんをイベントに適用するポリシーを示します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-124">Indicates the policy to apply to events that arrive at the output and cannot be written to the external storage due to being malformed (missing column values, column values of wrong type or size).</span></span> <span data-ttu-id="07ce0-125">使用可能な値が含まれます: 'Stop'、'Drop'</span><span class="sxs-lookup"><span data-stu-id="07ce0-125">Possible values include: 'Stop', 'Drop'</span></span></param>
        <param name="eventsOutOfOrderMaxDelayInSeconds"><span data-ttu-id="07ce0-126">順序不定なイベントを調整する順序に戻ります、秒単位で許容できる最大遅延。</span><span class="sxs-lookup"><span data-stu-id="07ce0-126">The maximum tolerable delay in seconds where out-of-order events can be adjusted to be back in order.</span></span></param>
        <param name="eventsLateArrivalMaxDelayInSeconds"><span data-ttu-id="07ce0-127">遅れて到着するイベントが含まれるなります秒単位で最大の遅延時間を許容できます。</span><span class="sxs-lookup"><span data-stu-id="07ce0-127">The maximum tolerable delay in seconds where events arriving late could be included.</span></span>  <span data-ttu-id="07ce0-128">サポートされている範囲は-1 1814399 (20.23:59:59 日) を指定し、-1 を使用して、無期限に待機を指定します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-128">Supported range is -1 to 1814399 (20.23:59:59 days) and -1 is used to specify wait indefinitely.</span></span> <span data-ttu-id="07ce0-129">プロパティがない場合は-1 の値が解釈されます。</span><span class="sxs-lookup"><span data-stu-id="07ce0-129">If the property is absent, it is interpreted to have a value of -1.</span></span></param>
        <param name="dataLocale"><span data-ttu-id="07ce0-130">Stream analytics ジョブのデータのロケールです。</span><span class="sxs-lookup"><span data-stu-id="07ce0-130">The data locale of the stream analytics job.</span></span> <span data-ttu-id="07ce0-131">値がセット https://msdn.microsoft.com/en-us/library/system.globalization.culturetypes(v=vs.110).aspx. からサポートされている .NET カルチャの名前を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-131">Value should be the name of a supported .NET Culture from the set https://msdn.microsoft.com/en-us/library/system.globalization.culturetypes(v=vs.110).aspx.</span></span>
            <span data-ttu-id="07ce0-132">指定しない場合は、' EN-US ' に既定値です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-132">Defaults to 'en-US' if none specified.</span></span></param>
        <param name="compatibilityLevel"><span data-ttu-id="07ce0-133">ストリーミング ジョブの特定のランタイム動作を制御します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-133">Controls certain runtime behaviors of the streaming job.</span></span> <span data-ttu-id="07ce0-134">使用可能な値が含まれます: '1.0'</span><span class="sxs-lookup"><span data-stu-id="07ce0-134">Possible values include: '1.0'</span></span></param>
        <param name="createdDate"><span data-ttu-id="07ce0-135">値は、ISO 8601 形式のストリーミング ジョブが作成されたことを示す UTC タイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="07ce0-135">Value is an ISO-8601 formatted UTC timestamp indicating when the streaming job was created.</span></span></param>
        <param name="inputs"><span data-ttu-id="07ce0-136">ストリーミング ジョブに対する 1 つまたは複数の入力の一覧。</span><span class="sxs-lookup"><span data-stu-id="07ce0-136">A list of one or more inputs to the streaming job.</span></span> <span data-ttu-id="07ce0-137">PUT 要求でこのプロパティを指定する場合、各入力の name プロパティが必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-137">The name property for each input is required when specifying this property in a PUT request.</span></span> <span data-ttu-id="07ce0-138">PATCH 操作では、このプロパティを変更できません。</span><span class="sxs-lookup"><span data-stu-id="07ce0-138">This property cannot be modify via a PATCH operation.</span></span> <span data-ttu-id="07ce0-139">個々 の入力の修正プログラムを適用して利用できる API を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-139">You must use the PATCH API available for the individual input.</span></span></param>
        <param name="transformation"><span data-ttu-id="07ce0-140">クエリと、ストリーミング ジョブに使用するストリーミング ユニットの数を示します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-140">Indicates the query and the number of streaming units to use for the streaming job.</span></span> <span data-ttu-id="07ce0-141">PUT 要求でこのプロパティを指定する場合、変換の name プロパティが必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-141">The name property of the transformation is required when specifying this property in a PUT request.</span></span> <span data-ttu-id="07ce0-142">PATCH 操作では、このプロパティを変更できません。</span><span class="sxs-lookup"><span data-stu-id="07ce0-142">This property cannot be modify via a PATCH operation.</span></span>
            <span data-ttu-id="07ce0-143">個々 の変換の修正プログラムを適用して利用できる API を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-143">You must use the PATCH API available for the individual tranformation.</span></span></param>
        <param name="outputs"><span data-ttu-id="07ce0-144">ストリーミング ジョブの 1 つまたは複数の出力の一覧です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-144">A list of one or more outputs for the streaming job.</span></span> <span data-ttu-id="07ce0-145">PUT 要求でこのプロパティを指定する場合、各出力の name プロパティが必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-145">The name property for each output is required when specifying this property in a PUT request.</span></span> <span data-ttu-id="07ce0-146">PATCH 操作では、このプロパティを変更できません。</span><span class="sxs-lookup"><span data-stu-id="07ce0-146">This property cannot be modify via a PATCH operation.</span></span> <span data-ttu-id="07ce0-147">個々 の出力の修正プログラムを適用して利用できる API を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-147">You must use the PATCH API available for the individual output.</span></span></param>
        <param name="functions"><span data-ttu-id="07ce0-148">ストリーミング ジョブの 1 つまたは複数の関数の一覧です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-148">A list of one or more functions for the streaming job.</span></span> <span data-ttu-id="07ce0-149">PUT 要求でこのプロパティを指定する場合、各関数は、name プロパティが必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-149">The name property for each function is required when specifying this property in a PUT request.</span></span> <span data-ttu-id="07ce0-150">PATCH 操作では、このプロパティを変更できません。</span><span class="sxs-lookup"><span data-stu-id="07ce0-150">This property cannot be modify via a PATCH operation.</span></span> <span data-ttu-id="07ce0-151">個々 の変換の修正プログラムを適用して利用できる API を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-151">You must use the PATCH API available for the individual transformation.</span></span></param>
        <param name="etag"><span data-ttu-id="07ce0-152">ストリーミング ジョブの現在のエンティティ タグ。</span><span class="sxs-lookup"><span data-stu-id="07ce0-152">The current entity tag for the streaming job.</span></span>
            <span data-ttu-id="07ce0-153">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-153">This is an opaque string.</span></span> <span data-ttu-id="07ce0-154">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="07ce0-154">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="07ce0-155">使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</span><span class="sxs-lookup"><span data-stu-id="07ce0-155">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span></param>
        <summary>
            <span data-ttu-id="07ce0-156">StreamingJob クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-156">Initializes a new instance of the StreamingJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompatibilityLevel">
      <MemberSignature Language="C#" Value="public string CompatibilityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CompatibilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CompatibilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property CompatibilityLevel As String" />
      <MemberSignature Language="F#" Value="member this.CompatibilityLevel : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CompatibilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.compatibilityLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-157">取得またはコントロールのストリーミング ジョブの特定のランタイム動作を設定します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-157">Gets or sets controls certain runtime behaviors of the streaming job.</span></span> <span data-ttu-id="07ce0-158">使用可能な値が含まれます: '1.0'</span><span class="sxs-lookup"><span data-stu-id="07ce0-158">Possible values include: '1.0'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CreatedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CreatedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-159">値を取得は、ISO 8601 形式のストリーミング ジョブが作成されたことを示す UTC タイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="07ce0-159">Gets value is an ISO-8601 formatted UTC timestamp indicating when the streaming job was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLocale">
      <MemberSignature Language="C#" Value="public string DataLocale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataLocale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.DataLocale" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLocale As String" />
      <MemberSignature Language="F#" Value="member this.DataLocale : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.DataLocale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataLocale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-160">取得または stream analytics ジョブのデータのロケールを設定します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-160">Gets or sets the data locale of the stream analytics job.</span></span> <span data-ttu-id="07ce0-161">値がセット https://msdn.microsoft.com/en-us/library/system.globalization.culturetypes(v=vs.110).aspx. からサポートされている .NET カルチャの名前を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-161">Value should be the name of a supported .NET Culture from the set https://msdn.microsoft.com/en-us/library/system.globalization.culturetypes(v=vs.110).aspx.</span></span>
            <span data-ttu-id="07ce0-162">指定しない場合は、' EN-US ' に既定値です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-162">Defaults to 'en-US' if none specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-163">ストリーミング ジョブの現在のエンティティ タグを取得します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-163">Gets the current entity tag for the streaming job.</span></span> <span data-ttu-id="07ce0-164">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-164">This is an opaque string.</span></span> <span data-ttu-id="07ce0-165">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="07ce0-165">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="07ce0-166">使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</span><span class="sxs-lookup"><span data-stu-id="07ce0-166">You can also use it in the If-Match or If-None-Match headers for write operations for optimistic concurrency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsLateArrivalMaxDelayInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EventsLateArrivalMaxDelayInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EventsLateArrivalMaxDelayInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsLateArrivalMaxDelayInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsLateArrivalMaxDelayInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EventsLateArrivalMaxDelayInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsLateArrivalMaxDelayInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventsLateArrivalMaxDelayInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-167">取得または遅延到着したイベントが含まれるなります許容量の最大遅延時間を秒単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-167">Gets or sets the maximum tolerable delay in seconds where events arriving late could be included.</span></span>  <span data-ttu-id="07ce0-168">サポートされている範囲は-1 1814399 (20.23:59:59 日) を指定し、-1 を使用して、無期限に待機を指定します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-168">Supported range is -1 to 1814399 (20.23:59:59 days) and -1 is used to specify wait indefinitely.</span></span> <span data-ttu-id="07ce0-169">プロパティがない場合は-1 の値が解釈されます。</span><span class="sxs-lookup"><span data-stu-id="07ce0-169">If the property is absent, it is interpreted to have a value of -1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsOutOfOrderMaxDelayInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EventsOutOfOrderMaxDelayInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EventsOutOfOrderMaxDelayInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderMaxDelayInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsOutOfOrderMaxDelayInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EventsOutOfOrderMaxDelayInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderMaxDelayInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventsOutOfOrderMaxDelayInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-170">取得またはする順序に戻りますを順序不定なイベントを調整できる最大許容遅延時間を秒単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-170">Gets or sets the maximum tolerable delay in seconds where out-of-order events can be adjusted to be back in order.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsOutOfOrderPolicy">
      <MemberSignature Language="C#" Value="public string EventsOutOfOrderPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventsOutOfOrderPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsOutOfOrderPolicy As String" />
      <MemberSignature Language="F#" Value="member this.EventsOutOfOrderPolicy : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventsOutOfOrderPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-171">取得または設定は、入力イベント ストリームで順序どおりに到着したイベントに適用するポリシーを示します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-171">Gets or sets indicates the policy to apply to events that arrive out of order in the input event stream.</span></span> <span data-ttu-id="07ce0-172">使用可能な値が含まれます: '調整'、'Drop'</span><span class="sxs-lookup"><span data-stu-id="07ce0-172">Possible values include: 'Adjust', 'Drop'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Functions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; Functions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; Functions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Functions" />
      <MemberSignature Language="VB.NET" Value="Public Property Functions As IList(Of Function)" />
      <MemberSignature Language="F#" Value="member this.Functions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Functions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.functions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-173">取得またはストリーミング ジョブの 1 つまたは複数の関数の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-173">Gets or sets a list of one or more functions for the streaming job.</span></span>
            <span data-ttu-id="07ce0-174">PUT 要求でこのプロパティを指定する場合、各関数は、name プロパティが必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-174">The name property for each function is required when specifying this property in a PUT request.</span></span> <span data-ttu-id="07ce0-175">PATCH 操作では、このプロパティを変更できません。</span><span class="sxs-lookup"><span data-stu-id="07ce0-175">This property cannot be modify via a PATCH operation.</span></span> <span data-ttu-id="07ce0-176">個々 の変換の修正プログラムを適用して利用できる API を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-176">You must use the PATCH API available for the individual transformation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; Inputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; Inputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Inputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Inputs As IList(Of Input)" />
      <MemberSignature Language="F#" Value="member this.Inputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Inputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-177">取得またはストリーミング ジョブに対する 1 つまたは複数の入力の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-177">Gets or sets a list of one or more inputs to the streaming job.</span></span> <span data-ttu-id="07ce0-178">PUT 要求でこのプロパティを指定する場合、各入力の name プロパティが必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-178">The name property for each input is required when specifying this property in a PUT request.</span></span> <span data-ttu-id="07ce0-179">PATCH 操作では、このプロパティを変更できません。</span><span class="sxs-lookup"><span data-stu-id="07ce0-179">This property cannot be modify via a PATCH operation.</span></span> <span data-ttu-id="07ce0-180">個々 の入力の修正プログラムを適用して利用できる API を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-180">You must use the PATCH API available for the individual input.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-181">ストリーミング ジョブを一意に識別する GUID を取得します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-181">Gets a GUID uniquely identifying the streaming job.</span></span> <span data-ttu-id="07ce0-182">この GUID は、ストリーミング ジョブの作成時に生成されます。</span><span class="sxs-lookup"><span data-stu-id="07ce0-182">This GUID is generated upon creation of the streaming job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobState">
      <MemberSignature Language="C#" Value="public string JobState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobState As String" />
      <MemberSignature Language="F#" Value="member this.JobState : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-183">取得では、ストリーミング ジョブの状態について説明します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-183">Gets describes the state of the streaming job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOutputEventTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastOutputEventTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastOutputEventTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.LastOutputEventTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastOutputEventTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastOutputEventTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.LastOutputEventTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastOutputEventTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-184">値を取得は、ストリーミング ジョブや、出力いないまだ生成されていることを示す null の最後の出力イベントの時刻を示すか、ISO 8601 フォーマットされたタイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="07ce0-184">Gets value is either an ISO-8601 formatted timestamp indicating the last output event time of the streaming job or null indicating that output has not yet been produced.</span></span> <span data-ttu-id="07ce0-185">複数の出力または複数のストリームでは、そのセットに最新の値を示します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-185">In case of multiple outputs or multiple streams, this shows the latest value in that set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputErrorPolicy">
      <MemberSignature Language="C#" Value="public string OutputErrorPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputErrorPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputErrorPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputErrorPolicy As String" />
      <MemberSignature Language="F#" Value="member this.OutputErrorPolicy : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputErrorPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputErrorPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-186">取得または設定は、出力に送られてくるし、外部ストレージことによって形式が正しくありません (不足している列の値、無効な型やサイズの列の値) に書き込むことはできませんをイベントに適用するポリシーを示します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-186">Gets or sets indicates the policy to apply to events that arrive at the output and cannot be written to the external storage due to being malformed (missing column values, column values of wrong type or size).</span></span> <span data-ttu-id="07ce0-187">使用可能な値が含まれます: 'Stop'、'Drop'</span><span class="sxs-lookup"><span data-stu-id="07ce0-187">Possible values include: 'Stop', 'Drop'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; Outputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; Outputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Outputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputs As IList(Of Output)" />
      <MemberSignature Language="F#" Value="member this.Outputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Outputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-188">取得またはストリーミング ジョブの 1 つまたは複数の出力の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-188">Gets or sets a list of one or more outputs for the streaming job.</span></span>
            <span data-ttu-id="07ce0-189">PUT 要求でこのプロパティを指定する場合、各出力の name プロパティが必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-189">The name property for each output is required when specifying this property in a PUT request.</span></span> <span data-ttu-id="07ce0-190">PATCH 操作では、このプロパティを変更できません。</span><span class="sxs-lookup"><span data-stu-id="07ce0-190">This property cannot be modify via a PATCH operation.</span></span> <span data-ttu-id="07ce0-191">個々 の出力の修正プログラムを適用して利用できる API を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-191">You must use the PATCH API available for the individual output.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartMode">
      <MemberSignature Language="C#" Value="public string OutputStartMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputStartMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartMode" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartMode As String" />
      <MemberSignature Language="F#" Value="member this.OutputStartMode : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputStartMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-192">取得または設定がこのプロパティは、作成時に、ジョブをすぐに開始することが必要な場合にのみ使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-192">Gets or sets this property should only be utilized when it is desired that the job be started immediately upon creation.</span></span> <span data-ttu-id="07ce0-193">値は JobStartTime、CustomTime、または lastoutputeventtime ですジョブを起動するたびに、出力イベント ストリームの開始位置を開始する必要がありますかどうかを示すためにあります outputStartTime プロパティを介して指定されたカスタム ユーザー タイムスタンプで開始 またはから開始します。最後のイベントは、時間を出力します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-193">Value may be JobStartTime, CustomTime, or LastOutputEventTime to indicate whether the starting point of the output event stream should start whenever the job is started, start at a custom user time stamp specified via the outputStartTime property, or start from the last event output time.</span></span> <span data-ttu-id="07ce0-194">使用可能な値が含まれます: 'JobStartTime'、'CustomTime'、'LastOutputEventTime'</span><span class="sxs-lookup"><span data-stu-id="07ce0-194">Possible values include: 'JobStartTime', 'CustomTime', 'LastOutputEventTime'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OutputStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OutputStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OutputStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-195">取得または設定の値がいずれか、ISO 8601 形式のタイムスタンプを出力イベント ストリームの開始位置を示すか、出力イベント ストリームが開始されていることを示す null をするたびに、ストリーミング ジョブが開始します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-195">Gets or sets value is either an ISO-8601 formatted time stamp that indicates the starting point of the output event stream, or null to indicate that the output event stream will start whenever the streaming job is started.</span></span> <span data-ttu-id="07ce0-196">このプロパティは、outputStartMode が CustomTime に設定されている場合、値にすることが必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-196">This property must have a value if outputStartMode is set to CustomTime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-197">取得では、ストリーミング ジョブのプロビジョニング状態について説明します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-197">Gets describes the provisioning status of the streaming job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.StreamAnalytics.Models.Sku with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-198">取得または設定は、ストリーミング ジョブの SKU をについて説明します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-198">Gets or sets describes the SKU of the streaming job.</span></span> <span data-ttu-id="07ce0-199">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-199">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Transformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Transformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Transformation" />
      <MemberSignature Language="VB.NET" Value="Public Property Transformation As Transformation" />
      <MemberSignature Language="F#" Value="member this.Transformation : Microsoft.Azure.Management.StreamAnalytics.Models.Transformation with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Transformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.transformation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07ce0-200">取得または設定は、クエリと、ストリーミング ジョブに使用するストリーミング ユニットの数を示します。</span><span class="sxs-lookup"><span data-stu-id="07ce0-200">Gets or sets indicates the query and the number of streaming units to use for the streaming job.</span></span> <span data-ttu-id="07ce0-201">PUT 要求でこのプロパティを指定する場合、変換の name プロパティが必要です。</span><span class="sxs-lookup"><span data-stu-id="07ce0-201">The name property of the transformation is required when specifying this property in a PUT request.</span></span> <span data-ttu-id="07ce0-202">PATCH 操作では、このプロパティを変更できません。</span><span class="sxs-lookup"><span data-stu-id="07ce0-202">This property cannot be modify via a PATCH operation.</span></span> <span data-ttu-id="07ce0-203">個々 の変換の修正プログラムを適用して利用できる API を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="07ce0-203">You must use the PATCH API available for the individual tranformation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>