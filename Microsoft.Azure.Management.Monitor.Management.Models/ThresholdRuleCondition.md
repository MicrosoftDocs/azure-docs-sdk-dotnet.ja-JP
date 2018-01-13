<Type Name="ThresholdRuleCondition" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition">
  <TypeSignature Language="C#" Value="public class ThresholdRuleCondition : Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ThresholdRuleCondition extends Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class ThresholdRuleCondition&#xA;Inherits RuleCondition" />
  <TypeSignature Language="F#" Value="type ThresholdRuleCondition = class&#xA;    inherit RuleCondition" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Azure.Management.Insights.Models.ThresholdRuleCondition")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f8e65-101">しきい値を超えたメトリックに基づいてルールの条件。</span><span class="sxs-lookup"><span data-stu-id="f8e65-101">A rule condition based on a metric crossing a threshold.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ThresholdRuleCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8e65-102">ThresholdRuleCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f8e65-102">Initializes a new instance of the ThresholdRuleCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ThresholdRuleCondition (Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator operatorProperty, double threshold, Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource = null, Nullable&lt;TimeSpan&gt; windowSize = null, Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationOperator&gt; timeAggregation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator operatorProperty, float64 threshold, class Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; windowSize, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationOperator&gt; timeAggregation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.#ctor(Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator,System.Double,Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource,System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationOperator})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operatorProperty As ConditionOperator, threshold As Double, Optional dataSource As RuleDataSource = null, Optional windowSize As Nullable(Of TimeSpan) = null, Optional timeAggregation As Nullable(Of TimeAggregationOperator) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition : Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator * double * Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationOperator&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition (operatorProperty, threshold, dataSource, windowSize, timeAggregation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operatorProperty" Type="Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator" />
        <Parameter Name="threshold" Type="System.Double" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource" />
        <Parameter Name="windowSize" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="timeAggregation" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationOperator&gt;" />
      </Parameters>
      <Docs>
        <param name="operatorProperty"><span data-ttu-id="f8e65-103">データとしきい値の比較に使用する演算子です。</span><span class="sxs-lookup"><span data-stu-id="f8e65-103">the operator used to compare the data and the threshold.</span></span> <span data-ttu-id="f8e65-104">使用可能な値が含まれます 'GreaterThan'、'GreaterThanOrEqual'、"LessThan"、"LessThanOrEqual"。</span><span class="sxs-lookup"><span data-stu-id="f8e65-104">Possible values include: 'GreaterThan', 'GreaterThanOrEqual', 'LessThan', 'LessThanOrEqual'</span></span></param>
        <param name="threshold"><span data-ttu-id="f8e65-105">アラートを有効にするしきい値です。</span><span class="sxs-lookup"><span data-stu-id="f8e65-105">the threshold value that activates the alert.</span></span></param>
        <param name="dataSource"><span data-ttu-id="f8e65-106">ルールがそのデータを収集元となるリソースです。</span><span class="sxs-lookup"><span data-stu-id="f8e65-106">the resource from which the rule collects its data.</span></span> <span data-ttu-id="f8e65-107">この種類のデータ ソースが必ず型 RuleMetricDataSource の。</span><span class="sxs-lookup"><span data-stu-id="f8e65-107">For this type dataSource will always be of type RuleMetricDataSource.</span></span></param>
        <param name="windowSize"><span data-ttu-id="f8e65-108">期間 (ISO 8601 期間形式) でのしきい値に基づいてアラート アクティビティを監視するために使用します。</span><span class="sxs-lookup"><span data-stu-id="f8e65-108">the period of time (in ISO 8601 duration format) that is used to monitor alert activity based on the threshold.</span></span> <span data-ttu-id="f8e65-109">5 分から 1 日の間でなければなりませんし、指定されている場合。</span><span class="sxs-lookup"><span data-stu-id="f8e65-109">If specified then it must be between 5 minutes and 1 day.</span></span></param>
        <param name="timeAggregation"><span data-ttu-id="f8e65-110">時間の集計演算子です。</span><span class="sxs-lookup"><span data-stu-id="f8e65-110">the time aggregation operator.</span></span> <span data-ttu-id="f8e65-111">どの時間の経過と共に収集されたデータを組み合わせる必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8e65-111">How the data that are collected should be combined over time.</span></span> <span data-ttu-id="f8e65-112">既定値は、メトリックの PrimaryAggregationType です。</span><span class="sxs-lookup"><span data-stu-id="f8e65-112">The default value is the PrimaryAggregationType of the Metric.</span></span> <span data-ttu-id="f8e65-113">使用可能な値が含まれます: '平均'、'最小'、'最大'、'Total'、'Last'</span><span class="sxs-lookup"><span data-stu-id="f8e65-113">Possible values include: 'Average', 'Minimum', 'Maximum', 'Total', 'Last'</span></span></param>
        <summary>
            <span data-ttu-id="f8e65-114">ThresholdRuleCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f8e65-114">Initializes a new instance of the ThresholdRuleCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatorProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator OperatorProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator OperatorProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.OperatorProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property OperatorProperty As ConditionOperator" />
      <MemberSignature Language="F#" Value="member this.OperatorProperty : Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.OperatorProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8e65-115">取得またはデータとしきい値の比較に使用する演算子を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8e65-115">Gets or sets the operator used to compare the data and the threshold.</span></span> <span data-ttu-id="f8e65-116">使用可能な値が含まれます 'GreaterThan'、'GreaterThanOrEqual'、"LessThan"、"LessThanOrEqual"。</span><span class="sxs-lookup"><span data-stu-id="f8e65-116">Possible values include: 'GreaterThan', 'GreaterThanOrEqual', 'LessThan', 'LessThanOrEqual'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Threshold">
      <MemberSignature Language="C#" Value="public double Threshold { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Threshold" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.Threshold" />
      <MemberSignature Language="VB.NET" Value="Public Property Threshold As Double" />
      <MemberSignature Language="F#" Value="member this.Threshold : double with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.Threshold" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="threshold")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8e65-117">取得またはアラートがアクティブにするしきい値を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8e65-117">Gets or sets the threshold value that activates the alert.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeAggregation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationOperator&gt; TimeAggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationOperator&gt; TimeAggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.TimeAggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeAggregation As Nullable(Of TimeAggregationOperator)" />
      <MemberSignature Language="F#" Value="member this.TimeAggregation : Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationOperator&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.TimeAggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeAggregation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationOperator&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8e65-118">取得または時間の集計演算子を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8e65-118">Gets or sets the time aggregation operator.</span></span> <span data-ttu-id="f8e65-119">どの時間の経過と共に収集されたデータを組み合わせる必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8e65-119">How the data that are collected should be combined over time.</span></span> <span data-ttu-id="f8e65-120">既定値は、メトリックの PrimaryAggregationType です。</span><span class="sxs-lookup"><span data-stu-id="f8e65-120">The default value is the PrimaryAggregationType of the Metric.</span></span> <span data-ttu-id="f8e65-121">使用可能な値が含まれます: '平均'、'最小'、'最大'、'Total'、'Last'</span><span class="sxs-lookup"><span data-stu-id="f8e65-121">Possible values include: 'Average', 'Minimum', 'Maximum', 'Total', 'Last'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="thresholdRuleCondition.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8e65-122">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f8e65-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f8e65-123">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f8e65-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WindowSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; WindowSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; WindowSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.WindowSize" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowSize As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.WindowSize : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ThresholdRuleCondition.WindowSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8e65-124">取得または設定の時間 (ISO 8601 期間形式) のしきい値に基づいてアラート アクティビティを監視するために使用します。</span><span class="sxs-lookup"><span data-stu-id="f8e65-124">Gets or sets the period of time (in ISO 8601 duration format) that is used to monitor alert activity based on the threshold.</span></span> <span data-ttu-id="f8e65-125">5 分から 1 日の間でなければなりませんし、指定されている場合。</span><span class="sxs-lookup"><span data-stu-id="f8e65-125">If specified then it must be between 5 minutes and 1 day.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>