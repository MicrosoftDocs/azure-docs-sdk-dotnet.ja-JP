<Type Name="UsageMetric" FullName="Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric">
  <TypeSignature Language="C#" Value="public class UsageMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UsageMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class UsageMetric" />
  <TypeSignature Language="F#" Value="type UsageMetric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="820eb-101">リソースの使用方法を説明するメトリックです。</span><span class="sxs-lookup"><span data-stu-id="820eb-101">A metric describing the usage of a resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="820eb-102">UsageMetric クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="820eb-102">Initializes a new instance of the UsageMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageMetric (Microsoft.Azure.Management.OperationalInsights.Models.MetricName name = null, string unit = null, Nullable&lt;double&gt; currentValue = null, Nullable&lt;double&gt; limit = null, Nullable&lt;DateTime&gt; nextResetTime = null, string quotaPeriod = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.OperationalInsights.Models.MetricName name, string unit, valuetype System.Nullable`1&lt;float64&gt; currentValue, valuetype System.Nullable`1&lt;float64&gt; limit, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextResetTime, string quotaPeriod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.#ctor(Microsoft.Azure.Management.OperationalInsights.Models.MetricName,System.String,System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As MetricName = null, Optional unit As String = null, Optional currentValue As Nullable(Of Double) = null, Optional limit As Nullable(Of Double) = null, Optional nextResetTime As Nullable(Of DateTime) = null, Optional quotaPeriod As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric : Microsoft.Azure.Management.OperationalInsights.Models.MetricName * string * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric (name, unit, currentValue, limit, nextResetTime, quotaPeriod)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.OperationalInsights.Models.MetricName" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="nextResetTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="quotaPeriod" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="820eb-103">メトリックの名前。</span><span class="sxs-lookup"><span data-stu-id="820eb-103">The name of the metric.</span></span></param>
        <param name="unit"><span data-ttu-id="820eb-104">メトリックに使用する単位です。</span><span class="sxs-lookup"><span data-stu-id="820eb-104">The units used for the metric.</span></span></param>
        <param name="currentValue"><span data-ttu-id="820eb-105">メトリックの現在の値。</span><span class="sxs-lookup"><span data-stu-id="820eb-105">The current value of the metric.</span></span></param>
        <param name="limit"><span data-ttu-id="820eb-106">メトリックのクォータ制限します。</span><span class="sxs-lookup"><span data-stu-id="820eb-106">The quota limit for the metric.</span></span></param>
        <param name="nextResetTime"><span data-ttu-id="820eb-107">メトリックの値をリセットする時刻。</span><span class="sxs-lookup"><span data-stu-id="820eb-107">The time that the metric's value will reset.</span></span></param>
        <param name="quotaPeriod"><span data-ttu-id="820eb-108">値の間の時間の長さを決定するクォータ期間がリセットされます。</span><span class="sxs-lookup"><span data-stu-id="820eb-108">The quota period that determines the length of time between value resets.</span></span></param>
        <summary>
            <span data-ttu-id="820eb-109">UsageMetric クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="820eb-109">Initializes a new instance of the UsageMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="820eb-110">取得またはメトリックの現在の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="820eb-110">Gets or sets the current value of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="820eb-111">取得またはメトリックのクォータ制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="820eb-111">Gets or sets the quota limit for the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.MetricName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.MetricName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As MetricName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.OperationalInsights.Models.MetricName with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.MetricName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="820eb-112">取得またはメトリックの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="820eb-112">Gets or sets the name of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextResetTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextResetTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextResetTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.NextResetTime" />
      <MemberSignature Language="VB.NET" Value="Public Property NextResetTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextResetTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.NextResetTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextResetTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="820eb-113">取得またはメトリックの値をリセットする時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="820eb-113">Gets or sets the time that the metric's value will reset.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotaPeriod">
      <MemberSignature Language="C#" Value="public string QuotaPeriod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotaPeriod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.QuotaPeriod" />
      <MemberSignature Language="VB.NET" Value="Public Property QuotaPeriod As String" />
      <MemberSignature Language="F#" Value="member this.QuotaPeriod : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.QuotaPeriod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quotaPeriod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="820eb-114">取得または値のリセット間隔の長さを決定するクォータを設定します。</span><span class="sxs-lookup"><span data-stu-id="820eb-114">Gets or sets the quota period that determines the length of time between value resets.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
            <span data-ttu-id="820eb-115">取得またはメトリックに使用する単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="820eb-115">Gets or sets the units used for the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>