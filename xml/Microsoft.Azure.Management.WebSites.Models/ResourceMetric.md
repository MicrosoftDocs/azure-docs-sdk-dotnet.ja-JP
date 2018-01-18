<Type Name="ResourceMetric" FullName="Microsoft.Azure.Management.WebSites.Models.ResourceMetric">
  <TypeSignature Language="C#" Value="public class ResourceMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ResourceMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceMetric" />
  <TypeSignature Language="F#" Value="type ResourceMetric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="660b4-101">任意のリソースのメトリックを表すオブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="660b4-101">Object representing a metric for any resource .</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="660b4-102">ResourceMetric クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="660b4-102">Initializes a new instance of the ResourceMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceMetric (Microsoft.Azure.Management.WebSites.Models.ResourceMetricName name = null, string unit = null, string timeGrain = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string resourceId = null, string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricValue&gt; metricValues = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricProperty&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.WebSites.Models.ResourceMetricName name, string unit, string timeGrain, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string resourceId, string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricValue&gt; metricValues, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricProperty&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.#ctor(Microsoft.Azure.Management.WebSites.Models.ResourceMetricName,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.ResourceMetricValue},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.ResourceMetricProperty})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As ResourceMetricName = null, Optional unit As String = null, Optional timeGrain As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional resourceId As String = null, Optional id As String = null, Optional metricValues As IList(Of ResourceMetricValue) = null, Optional properties As IList(Of ResourceMetricProperty) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ResourceMetric : Microsoft.Azure.Management.WebSites.Models.ResourceMetricName * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricValue&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricProperty&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.ResourceMetric" Usage="new Microsoft.Azure.Management.WebSites.Models.ResourceMetric (name, unit, timeGrain, startTime, endTime, resourceId, id, metricValues, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.WebSites.Models.ResourceMetricName" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="metricValues" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricValue&gt;" />
        <Parameter Name="properties" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricProperty&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="660b4-103">メトリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="660b4-103">Name of metric.</span></span></param>
        <param name="unit"><span data-ttu-id="660b4-104">メトリックの単位です。</span><span class="sxs-lookup"><span data-stu-id="660b4-104">Metric unit.</span></span></param>
        <param name="timeGrain"><span data-ttu-id="660b4-105">メトリックの粒度。</span><span class="sxs-lookup"><span data-stu-id="660b4-105">Metric granularity.</span></span> <span data-ttu-id="660b4-106">例: PT1H、PT5M、P1D</span><span class="sxs-lookup"><span data-stu-id="660b4-106">E.g PT1H, PT5M, P1D</span></span></param>
        <param name="startTime"><span data-ttu-id="660b4-107">メトリックの開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="660b4-107">Metric start time.</span></span></param>
        <param name="endTime"><span data-ttu-id="660b4-108">メトリックの終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="660b4-108">Metric end time.</span></span></param>
        <param name="resourceId"><span data-ttu-id="660b4-109">メトリック リソース id。</span><span class="sxs-lookup"><span data-stu-id="660b4-109">Metric resource Id.</span></span></param>
        <param name="id"><span data-ttu-id="660b4-110">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="660b4-110">Resource Id.</span></span></param>
        <param name="metricValues"><span data-ttu-id="660b4-111">メトリックの値。</span><span class="sxs-lookup"><span data-stu-id="660b4-111">Metric values.</span></span></param>
        <param name="properties"><span data-ttu-id="660b4-112">プロパティ</span><span class="sxs-lookup"><span data-stu-id="660b4-112">Properties.</span></span></param>
        <summary>
            <span data-ttu-id="660b4-113">ResourceMetric クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="660b4-113">Initializes a new instance of the ResourceMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetric.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            <span data-ttu-id="660b4-114">メトリックの終了時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="660b4-114">Gets metric end time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetric.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="660b4-115">リソース id。 を取得します。</span><span class="sxs-lookup"><span data-stu-id="660b4-115">Gets resource Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricValues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricValue&gt; MetricValues { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricValue&gt; MetricValues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.MetricValues" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricValues As IList(Of ResourceMetricValue)" />
      <MemberSignature Language="F#" Value="member this.MetricValues : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricValue&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetric.MetricValues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricValues")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricValue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="660b4-116">メトリックの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="660b4-116">Gets metric values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.ResourceMetricName Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.ResourceMetricName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As ResourceMetricName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.WebSites.Models.ResourceMetricName" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ResourceMetricName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="660b4-117">メトリックの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="660b4-117">Gets name of metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricProperty&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricProperty&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IList(Of ResourceMetricProperty)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricProperty&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetric.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricProperty&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="660b4-118">プロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="660b4-118">Gets properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetric.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            <span data-ttu-id="660b4-119">取得メトリック リソース id。</span><span class="sxs-lookup"><span data-stu-id="660b4-119">Gets metric resource Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetric.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            <span data-ttu-id="660b4-120">メトリックの開始時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="660b4-120">Gets metric start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetric.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            <span data-ttu-id="660b4-121">メトリックの粒度を取得します。</span><span class="sxs-lookup"><span data-stu-id="660b4-121">Gets metric granularity.</span></span> <span data-ttu-id="660b4-122">例: PT1H、PT5M、P1D</span><span class="sxs-lookup"><span data-stu-id="660b4-122">E.g PT1H, PT5M, P1D</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ResourceMetric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.WebSites.Models.ResourceMetric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="660b4-123">メトリックの単位を取得します。</span><span class="sxs-lookup"><span data-stu-id="660b4-123">Gets metric unit.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>