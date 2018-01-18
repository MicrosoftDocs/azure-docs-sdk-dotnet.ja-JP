<Type Name="MetricDefinition" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition">
  <TypeSignature Language="C#" Value="public class MetricDefinition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricDefinition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricDefinition" />
  <TypeSignature Language="F#" Value="type MetricDefinition = class" />
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
            <span data-ttu-id="6e06e-101">監視メトリックの定義。</span><span class="sxs-lookup"><span data-stu-id="6e06e-101">The monitoring metric definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6e06e-102">MetricDefinition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e06e-102">Initializes a new instance of the MetricDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricDefinition (Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName name = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; unit = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; primaryAggregationType = null, string resourceId = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; metricAvailabilities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; dimensions = null, string category = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; unit, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; primaryAggregationType, string resourceId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; metricAvailabilities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; dimensions, string category, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity},System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As MetricName = null, Optional unit As Nullable(Of MetricUnit) = null, Optional primaryAggregationType As Nullable(Of MetricAggregationType) = null, Optional resourceId As String = null, Optional metricAvailabilities As IList(Of MetricAvailablity) = null, Optional dimensions As IList(Of MetricDimension) = null, Optional category As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition : Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition (name, unit, primaryAggregationType, resourceId, metricAvailabilities, dimensions, category, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName" />
        <Parameter Name="unit" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt;" />
        <Parameter Name="primaryAggregationType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt;" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="metricAvailabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt;" />
        <Parameter Name="dimensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt;" />
        <Parameter Name="category" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="6e06e-103">メトリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="6e06e-103">The metric name.</span></span></param>
        <param name="unit"><span data-ttu-id="6e06e-104">メトリックの単位です。</span><span class="sxs-lookup"><span data-stu-id="6e06e-104">The metric unit.</span></span> <span data-ttu-id="6e06e-105">使用可能な値が含まれます: 'バイト'、'BytesPerSecond'、'Count'、'CountPerSecond'、'%'、"Seconds"</span><span class="sxs-lookup"><span data-stu-id="6e06e-105">Possible values include: 'Bytes', 'BytesPerSecond', 'Count', 'CountPerSecond', 'Percent', 'Seconds'</span></span></param>
        <param name="primaryAggregationType"><span data-ttu-id="6e06e-106">メトリックの集計の種類。</span><span class="sxs-lookup"><span data-stu-id="6e06e-106">The metric aggregation type.</span></span>
            <span data-ttu-id="6e06e-107">使用可能な値が含まれます: '平均'、'Last'、'最大'、'最小'、'None'、'Total'</span><span class="sxs-lookup"><span data-stu-id="6e06e-107">Possible values include: 'Average', 'Last', 'Maximum', 'Minimum', 'None', 'Total'</span></span></param>
        <param name="resourceId"><span data-ttu-id="6e06e-108">メトリック ソース id。</span><span class="sxs-lookup"><span data-stu-id="6e06e-108">The metric source ID.</span></span></param>
        <param name="metricAvailabilities"><span data-ttu-id="6e06e-109">使用可能なメトリック粒度。</span><span class="sxs-lookup"><span data-stu-id="6e06e-109">The available metric granularities.</span></span></param>
        <param name="dimensions"><span data-ttu-id="6e06e-110">使用可能なメトリックのディメンションです。</span><span class="sxs-lookup"><span data-stu-id="6e06e-110">The available metric dimensions.</span></span></param>
        <param name="category"><span data-ttu-id="6e06e-111">メトリックのカテゴリ。</span><span class="sxs-lookup"><span data-stu-id="6e06e-111">The category of the metric.</span></span></param>
        <param name="type"><span data-ttu-id="6e06e-112">メトリック定義の型。</span><span class="sxs-lookup"><span data-stu-id="6e06e-112">The metric definition type.</span></span></param>
        <summary>
            <span data-ttu-id="6e06e-113">MetricDefinition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6e06e-113">Initializes a new instance of the MetricDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public string Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As String" />
      <MemberSignature Language="F#" Value="member this.Category : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e06e-114">取得またはメトリックのカテゴリを設定します。</span><span class="sxs-lookup"><span data-stu-id="6e06e-114">Gets or sets the category of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dimensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; Dimensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; Dimensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Dimensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Dimensions As IList(Of MetricDimension)" />
      <MemberSignature Language="F#" Value="member this.Dimensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Dimensions" />
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
            <span data-ttu-id="6e06e-115">取得または使用可能なメトリックのディメンションを設定します。</span><span class="sxs-lookup"><span data-stu-id="6e06e-115">Gets or sets the available metric dimensions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricAvailabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; MetricAvailabilities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; MetricAvailabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.MetricAvailabilities" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricAvailabilities As IList(Of MetricAvailablity)" />
      <MemberSignature Language="F#" Value="member this.MetricAvailabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.MetricAvailabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricAvailabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e06e-116">取得または使用可能なメトリックの粒度を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e06e-116">Gets or sets the available metric granularities.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As MetricName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Name" />
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
            <span data-ttu-id="6e06e-117">取得またはメトリック名を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e06e-117">Gets or sets the metric name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAggregationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; PrimaryAggregationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; PrimaryAggregationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.PrimaryAggregationType" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryAggregationType As Nullable(Of MetricAggregationType)" />
      <MemberSignature Language="F#" Value="member this.PrimaryAggregationType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.PrimaryAggregationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryAggregationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e06e-118">取得またはメトリックの集計の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e06e-118">Gets or sets the metric aggregation type.</span></span> <span data-ttu-id="6e06e-119">使用可能な値が含まれます: '平均'、'Last'、'最大'、'最小'、'None'、'Total'</span><span class="sxs-lookup"><span data-stu-id="6e06e-119">Possible values include: 'Average', 'Last', 'Maximum', 'Minimum', 'None', 'Total'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.ResourceId" />
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
            <span data-ttu-id="6e06e-120">取得または設定、メトリック ソース id です。</span><span class="sxs-lookup"><span data-stu-id="6e06e-120">Gets or sets the metric source ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Type" />
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
            <span data-ttu-id="6e06e-121">取得またはメトリックの定義の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e06e-121">Gets or sets the metric definition type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As Nullable(Of MetricUnit)" />
      <MemberSignature Language="F#" Value="member this.Unit : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Unit" />
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
            <span data-ttu-id="6e06e-122">取得またはメトリックの単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="6e06e-122">Gets or sets the metric unit.</span></span> <span data-ttu-id="6e06e-123">使用可能な値が含まれます: 'バイト'、'BytesPerSecond'、'Count'、'CountPerSecond'、'%'、"Seconds"</span><span class="sxs-lookup"><span data-stu-id="6e06e-123">Possible values include: 'Bytes', 'BytesPerSecond', 'Count', 'CountPerSecond', 'Percent', 'Seconds'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>