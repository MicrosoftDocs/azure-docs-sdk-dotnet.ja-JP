<Type Name="AlertFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter">
  <TypeSignature Language="C#" Value="public class AlertFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AlertFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class AlertFilter" />
  <TypeSignature Language="F#" Value="type AlertFilter = class" />
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
            <span data-ttu-id="3ac9a-101">アラートに使用する OData のフィルター</span><span class="sxs-lookup"><span data-stu-id="3ac9a-101">The OData filters to be used for Alert</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3ac9a-102">AlertFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-102">Initializes a new instance of the AlertFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AlertFilter (Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; status = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; severity = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; sourceType = null, string sourceName = null, Nullable&lt;DateTime&gt; appearedOnTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; status, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; severity, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; sourceType, string sourceName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; appearedOnTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.#ctor(System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType},System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As Nullable(Of AlertStatus) = null, Optional severity As Nullable(Of AlertSeverity) = null, Optional sourceType As Nullable(Of AlertSourceType) = null, Optional sourceName As String = null, Optional appearedOnTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter (status, severity, sourceType, sourceName, appearedOnTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt;" />
        <Parameter Name="severity" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt;" />
        <Parameter Name="sourceType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt;" />
        <Parameter Name="sourceName" Type="System.String" />
        <Parameter Name="appearedOnTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="3ac9a-103">フィルター選択されるアラートの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-103">Specifies the status of the alerts to be filtered.</span></span> <span data-ttu-id="3ac9a-104">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-104">Only 'Equality' operator is supported for this property.</span></span>
            <span data-ttu-id="3ac9a-105">使用可能な値が含まれます: 'Active'、'オフ'</span><span class="sxs-lookup"><span data-stu-id="3ac9a-105">Possible values include: 'Active', 'Cleared'</span></span></param>
        <param name="severity"><span data-ttu-id="3ac9a-106">フィルター選択されるアラートの重要度を指定します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-106">Specifies the severity of the alerts to be filtered.</span></span> <span data-ttu-id="3ac9a-107">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-107">Only 'Equality' operator is supported for this property.</span></span>
            <span data-ttu-id="3ac9a-108">使用可能な値が含まれます: '情報'、'警告'、'重大'</span><span class="sxs-lookup"><span data-stu-id="3ac9a-108">Possible values include: 'Informational', 'Warning', 'Critical'</span></span></param>
        <param name="sourceType"><span data-ttu-id="3ac9a-109">フィルター選択されるアラートのソースの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-109">Specifies the source type of the alerts to be filtered.</span></span> <span data-ttu-id="3ac9a-110">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-110">Only 'Equality' operator is supported for this property.</span></span> <span data-ttu-id="3ac9a-111">使用可能な値が含まれます: 'Resource'、'デバイス'</span><span class="sxs-lookup"><span data-stu-id="3ac9a-111">Possible values include: 'Resource', 'Device'</span></span></param>
        <param name="sourceName"><span data-ttu-id="3ac9a-112">フィルター選択されるアラートのソース名を指定します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-112">Specifies the source name of the alerts to be filtered.</span></span> <span data-ttu-id="3ac9a-113">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-113">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="appearedOnTime"><span data-ttu-id="3ac9a-114">Appeared 時間 (UTC) のフィルター選択されるアラートを指定します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-114">Specifies the appeared time (in UTC) of the alerts to be filtered.</span></span> <span data-ttu-id="3ac9a-115">のみ '大きい-より' と 'いずれか小さいほう-より' 演算子はこのプロパティでサポートします。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-115">Only 'Greater-Than' and 'Lesser-Than' operators are supported for this property.</span></span></param>
        <summary>
            <span data-ttu-id="3ac9a-116">AlertFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-116">Initializes a new instance of the AlertFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppearedOnTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AppearedOnTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AppearedOnTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.AppearedOnTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AppearedOnTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AppearedOnTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.AppearedOnTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="appearedOnTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ac9a-117">取得または設定、appeared の時間 (UTC)、フィルター選択するアラートを指定します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-117">Gets or sets specifies the appeared time (in UTC) of the alerts to be filtered.</span></span> <span data-ttu-id="3ac9a-118">のみ '大きい-より' と 'いずれか小さいほう-より' 演算子はこのプロパティでサポートします。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-118">Only 'Greater-Than' and 'Lesser-Than' operators are supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; Severity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.Severity" />
      <MemberSignature Language="VB.NET" Value="Public Property Severity As Nullable(Of AlertSeverity)" />
      <MemberSignature Language="F#" Value="member this.Severity : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ac9a-119">取得または設定は、フィルター選択されるアラートの重要度を指定します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-119">Gets or sets specifies the severity of the alerts to be filtered.</span></span>
            <span data-ttu-id="3ac9a-120">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-120">Only 'Equality' operator is supported for this property.</span></span> <span data-ttu-id="3ac9a-121">使用可能な値が含まれます: '情報'、'警告'、'重大'</span><span class="sxs-lookup"><span data-stu-id="3ac9a-121">Possible values include: 'Informational', 'Warning', 'Critical'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceName">
      <MemberSignature Language="C#" Value="public string SourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.SourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceName As String" />
      <MemberSignature Language="F#" Value="member this.SourceName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.SourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ac9a-122">取得または設定は、フィルター選択されるアラートのソース名を指定します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-122">Gets or sets specifies the source name of the alerts to be filtered.</span></span> <span data-ttu-id="3ac9a-123">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-123">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; SourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; SourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.SourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceType As Nullable(Of AlertSourceType)" />
      <MemberSignature Language="F#" Value="member this.SourceType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.SourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSourceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ac9a-124">取得または設定は、フィルター選択されるアラートのソースの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-124">Gets or sets specifies the source type of the alerts to be filtered.</span></span> <span data-ttu-id="3ac9a-125">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-125">Only 'Equality' operator is supported for this property.</span></span>
            <span data-ttu-id="3ac9a-126">使用可能な値が含まれます: 'Resource'、'デバイス'</span><span class="sxs-lookup"><span data-stu-id="3ac9a-126">Possible values include: 'Resource', 'Device'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of AlertStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertFilter.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ac9a-127">取得または設定は、フィルター選択されるアラートの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-127">Gets or sets specifies the status of the alerts to be filtered.</span></span>
            <span data-ttu-id="3ac9a-128">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="3ac9a-128">Only 'Equality' operator is supported for this property.</span></span> <span data-ttu-id="3ac9a-129">使用可能な値が含まれます: 'Active'、'オフ'</span><span class="sxs-lookup"><span data-stu-id="3ac9a-129">Possible values include: 'Active', 'Cleared'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>