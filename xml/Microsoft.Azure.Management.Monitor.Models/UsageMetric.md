<Type Name="UsageMetric" FullName="Microsoft.Azure.Management.Monitor.Models.UsageMetric">
  <TypeSignature Language="C#" Value="public class UsageMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UsageMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.UsageMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class UsageMetric" />
  <TypeSignature Language="F#" Value="type UsageMetric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6d6e7-101">使用状況メトリック データ。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-101">Usage Metric data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.UsageMetric.#ctor" />
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
            <span data-ttu-id="6d6e7-102">UsageMetric クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-102">Initializes a new instance of the UsageMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageMetric (Microsoft.Azure.Management.Monitor.Models.LocalizableString name = null, Nullable&lt;double&gt; currentValue = null, string id = null, Nullable&lt;double&gt; limit = null, string unit = null, Nullable&lt;DateTime&gt; nextResetTime = null, Nullable&lt;TimeSpan&gt; quotaPeriod = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Monitor.Models.LocalizableString name, valuetype System.Nullable`1&lt;float64&gt; currentValue, string id, valuetype System.Nullable`1&lt;float64&gt; limit, string unit, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextResetTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; quotaPeriod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.UsageMetric.#ctor(Microsoft.Azure.Management.Monitor.Models.LocalizableString,System.Nullable{System.Double},System.String,System.Nullable{System.Double},System.String,System.Nullable{System.DateTime},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As LocalizableString = null, Optional currentValue As Nullable(Of Double) = null, Optional id As String = null, Optional limit As Nullable(Of Double) = null, Optional unit As String = null, Optional nextResetTime As Nullable(Of DateTime) = null, Optional quotaPeriod As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.UsageMetric : Microsoft.Azure.Management.Monitor.Models.LocalizableString * Nullable&lt;double&gt; * string * Nullable&lt;double&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.UsageMetric" Usage="new Microsoft.Azure.Management.Monitor.Models.UsageMetric (name, currentValue, id, limit, unit, nextResetTime, quotaPeriod)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="nextResetTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="quotaPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="6d6e7-103">使用状況メトリック名と表示名。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-103">the usage metric name and display name.</span></span></param>
        <param name="currentValue"><span data-ttu-id="6d6e7-104">使用状況メトリックの現在の値。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-104">the current value for the usage metric.</span></span></param>
        <param name="id"><span data-ttu-id="6d6e7-105">使用状況メトリックの id。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-105">the id for the usage metric.</span></span></param>
        <param name="limit"><span data-ttu-id="6d6e7-106">クォータは、使用状況メトリックを制限します。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-106">the quota limit the usage metric.</span></span></param>
        <param name="unit"><span data-ttu-id="6d6e7-107">使用状況メトリックの単位です。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-107">the unit for the usage metric.</span></span></param>
        <param name="nextResetTime"><span data-ttu-id="6d6e7-108">次は、現在の値の時刻をリセットします。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-108">the next reset time for the current value.</span></span></param>
        <param name="quotaPeriod"><span data-ttu-id="6d6e7-109">値をリセットするまでにかかる時間。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-109">the amount of time it takes to reset the value.</span></span></param>
        <summary>
            <span data-ttu-id="6d6e7-110">UsageMetric クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-110">Initializes a new instance of the UsageMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.UsageMetric.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.UsageMetric.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="6d6e7-111">取得または使用状況メトリックの現在の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-111">Gets or sets the current value for the usage metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.UsageMetric.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.UsageMetric.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="6d6e7-112">取得または使用状況メトリックの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-112">Gets or sets the id for the usage metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.UsageMetric.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.UsageMetric.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="6d6e7-113">取得または使用状況メトリックのクォータの上限を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-113">Gets or sets the quota limit the usage metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.UsageMetric.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.UsageMetric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d6e7-114">取得または使用状況メトリックの名前と表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-114">Gets or sets the usage metric name and display name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextResetTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextResetTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextResetTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.UsageMetric.NextResetTime" />
      <MemberSignature Language="VB.NET" Value="Public Property NextResetTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextResetTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.UsageMetric.NextResetTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="6d6e7-115">取得または設定、次へは、現在の値の時刻をリセットします。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-115">Gets or sets the next reset time for the current value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotaPeriod">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; QuotaPeriod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; QuotaPeriod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.UsageMetric.QuotaPeriod" />
      <MemberSignature Language="VB.NET" Value="Public Property QuotaPeriod As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.QuotaPeriod : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.UsageMetric.QuotaPeriod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quotaPeriod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d6e7-116">取得またはの値をリセットするまでにかかる時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-116">Gets or sets the amount of time it takes to reset the value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.UsageMetric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.UsageMetric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="6d6e7-117">取得または使用状況メトリックの単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-117">Gets or sets the unit for the usage metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.UsageMetric.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="usageMetric.Validate " />
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
            <span data-ttu-id="6d6e7-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6d6e7-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6d6e7-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>