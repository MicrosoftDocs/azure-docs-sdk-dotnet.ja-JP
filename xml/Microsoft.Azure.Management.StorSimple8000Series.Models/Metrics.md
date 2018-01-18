<Type Name="Metrics" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics">
  <TypeSignature Language="C#" Value="public class Metrics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Metrics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics" />
  <TypeSignature Language="VB.NET" Value="Public Class Metrics" />
  <TypeSignature Language="F#" Value="type Metrics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2201b-101">監視メトリック。</span><span class="sxs-lookup"><span data-stu-id="2201b-101">The monitoring metric.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metrics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2201b-102">メトリック クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2201b-102">Initializes a new instance of the Metrics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metrics (string resourceId = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string timeGrain = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; primaryAggregation = null, Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName name = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; dimensions = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; unit = null, string type = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData&gt; values = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string resourceId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string timeGrain, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; primaryAggregation, class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; dimensions, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; unit, string type, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData&gt; values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.#ctor(System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType},Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName,System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resourceId As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional timeGrain As String = null, Optional primaryAggregation As Nullable(Of MetricAggregationType) = null, Optional name As MetricName = null, Optional dimensions As IList(Of MetricDimension) = null, Optional unit As Nullable(Of MetricUnit) = null, Optional type As String = null, Optional values As IList(Of MetricData) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics : string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics (resourceId, startTime, endTime, timeGrain, primaryAggregation, name, dimensions, unit, type, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="primaryAggregation" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt;" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName" />
        <Parameter Name="dimensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt;" />
        <Parameter Name="unit" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt;" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData&gt;" />
      </Parameters>
      <Docs>
        <param name="resourceId"><span data-ttu-id="2201b-103">メトリック ソースの ID。</span><span class="sxs-lookup"><span data-stu-id="2201b-103">The ID of metric source.</span></span></param>
        <param name="startTime"><span data-ttu-id="2201b-104">メトリック データの開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="2201b-104">The start time of the metric data.</span></span></param>
        <param name="endTime"><span data-ttu-id="2201b-105">メトリック データの終了時刻。</span><span class="sxs-lookup"><span data-stu-id="2201b-105">The end time of the metric data.</span></span></param>
        <param name="timeGrain"><span data-ttu-id="2201b-106">メトリック データの時間粒度。</span><span class="sxs-lookup"><span data-stu-id="2201b-106">The time granularity of the metric data.</span></span></param>
        <param name="primaryAggregation"><span data-ttu-id="2201b-107">メトリックの集計の種類。</span><span class="sxs-lookup"><span data-stu-id="2201b-107">The metric aggregation type.</span></span>
            <span data-ttu-id="2201b-108">使用可能な値が含まれます: '平均'、'Last'、'最大'、'最小'、'None'、'Total'</span><span class="sxs-lookup"><span data-stu-id="2201b-108">Possible values include: 'Average', 'Last', 'Maximum', 'Minimum', 'None', 'Total'</span></span></param>
        <param name="name"><span data-ttu-id="2201b-109">メトリックの名前。</span><span class="sxs-lookup"><span data-stu-id="2201b-109">The name of the metric.</span></span></param>
        <param name="dimensions"><span data-ttu-id="2201b-110">メトリックのディメンションです。</span><span class="sxs-lookup"><span data-stu-id="2201b-110">The metric dimensions.</span></span></param>
        <param name="unit"><span data-ttu-id="2201b-111">メトリック データの単位。</span><span class="sxs-lookup"><span data-stu-id="2201b-111">The unit of the metric data.</span></span> <span data-ttu-id="2201b-112">使用可能な値が含まれます: 'バイト'、'BytesPerSecond'、'Count'、'CountPerSecond'、'%'、"Seconds"</span><span class="sxs-lookup"><span data-stu-id="2201b-112">Possible values include: 'Bytes', 'BytesPerSecond', 'Count', 'CountPerSecond', 'Percent', 'Seconds'</span></span></param>
        <param name="type"><span data-ttu-id="2201b-113">メトリック データの型。</span><span class="sxs-lookup"><span data-stu-id="2201b-113">The type of the metric data.</span></span></param>
        <param name="values"><span data-ttu-id="2201b-114">メトリック データの一覧。</span><span class="sxs-lookup"><span data-stu-id="2201b-114">The list of the metric data.</span></span></param>
        <summary>
            <span data-ttu-id="2201b-115">メトリック クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2201b-115">Initializes a new instance of the Metrics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dimensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; Dimensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; Dimensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.Dimensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Dimensions As IList(Of MetricDimension)" />
      <MemberSignature Language="F#" Value="member this.Dimensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.Dimensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dimensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201b-116">取得またはメートル寸法を設定します。</span><span class="sxs-lookup"><span data-stu-id="2201b-116">Gets or sets the metric dimensions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201b-117">取得またはメトリック データの終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="2201b-117">Gets or sets the end time of the metric data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As MetricName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201b-118">取得またはメトリックの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="2201b-118">Gets or sets the name of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAggregation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; PrimaryAggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; PrimaryAggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.PrimaryAggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryAggregation As Nullable(Of MetricAggregationType)" />
      <MemberSignature Language="F#" Value="member this.PrimaryAggregation : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.PrimaryAggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryAggregation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201b-119">取得またはメトリックの集計の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="2201b-119">Gets or sets the metric aggregation type.</span></span> <span data-ttu-id="2201b-120">使用可能な値が含まれます: '平均'、'Last'、'最大'、'最小'、'None'、'Total'</span><span class="sxs-lookup"><span data-stu-id="2201b-120">Possible values include: 'Average', 'Last', 'Maximum', 'Minimum', 'None', 'Total'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201b-121">取得またはメトリック ソースの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="2201b-121">Gets or sets the ID of metric source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201b-122">取得またはメトリック データの開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="2201b-122">Gets or sets the start time of the metric data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201b-123">取得またはメトリック データの時間粒度を設定します。</span><span class="sxs-lookup"><span data-stu-id="2201b-123">Gets or sets the time granularity of the metric data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201b-124">取得またはメトリック データの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="2201b-124">Gets or sets the type of the metric data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As Nullable(Of MetricUnit)" />
      <MemberSignature Language="F#" Value="member this.Unit : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201b-125">取得またはメトリック データの単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="2201b-125">Gets or sets the unit of the metric data.</span></span> <span data-ttu-id="2201b-126">使用可能な値が含まれます: 'バイト'、'BytesPerSecond'、'Count'、'CountPerSecond'、'%'、"Seconds"</span><span class="sxs-lookup"><span data-stu-id="2201b-126">Possible values include: 'Bytes', 'BytesPerSecond', 'Count', 'CountPerSecond', 'Percent', 'Seconds'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData&gt; Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As IList(Of MetricData)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201b-127">取得またはメトリック データの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="2201b-127">Gets or sets the list of the metric data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>