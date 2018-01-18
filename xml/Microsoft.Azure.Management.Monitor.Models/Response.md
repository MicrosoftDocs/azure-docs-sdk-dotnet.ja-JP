<Type Name="Response" FullName="Microsoft.Azure.Management.Monitor.Models.Response">
  <TypeSignature Language="C#" Value="public class Response" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Response extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.Response" />
  <TypeSignature Language="VB.NET" Value="Public Class Response" />
  <TypeSignature Language="F#" Value="type Response = class" />
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
            <span data-ttu-id="8c104-101">メトリックのクエリに対する応答です。</span><span class="sxs-lookup"><span data-stu-id="8c104-101">The response to a metrics query.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Response ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Response.#ctor" />
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
            <span data-ttu-id="8c104-102">応答のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8c104-102">Initializes a new instance of the Response class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Response (string timespan, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt; value, Nullable&lt;double&gt; cost = null, Nullable&lt;TimeSpan&gt; interval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timespan, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.Metric&gt; value, valuetype System.Nullable`1&lt;float64&gt; cost, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; interval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Response.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Models.Metric},System.Nullable{System.Double},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (timespan As String, value As IList(Of Metric), Optional cost As Nullable(Of Double) = null, Optional interval As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.Response : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt; * Nullable&lt;double&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.Response" Usage="new Microsoft.Azure.Management.Monitor.Models.Response (timespan, value, cost, interval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timespan" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt;" />
        <Parameter Name="cost" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="timespan"><span data-ttu-id="8c104-103">データを取得した timespan です。</span><span class="sxs-lookup"><span data-stu-id="8c104-103">The timespan for which the data was retrieved.</span></span> <span data-ttu-id="8c104-104">その値が連結された 2 つの datatimes から成るで区切られた '/' です。</span><span class="sxs-lookup"><span data-stu-id="8c104-104">Its value consists of two datatimes concatenated, separated by '/'.</span></span>  <span data-ttu-id="8c104-105">これは、後で調整可能性があり、最初に要求内容から返されます。</span><span class="sxs-lookup"><span data-stu-id="8c104-105">This may be adjusted in the future and returned back from what was originally requested.</span></span></param>
        <param name="value"><span data-ttu-id="8c104-106">コレクションの値。</span><span class="sxs-lookup"><span data-stu-id="8c104-106">the value of the collection.</span></span></param>
        <param name="cost"><span data-ttu-id="8c104-107">データの場合、クエリのコストを表す整数値。</span><span class="sxs-lookup"><span data-stu-id="8c104-107">The integer value representing the cost of the query, for data case.</span></span></param>
        <param name="interval"><span data-ttu-id="8c104-108">返されたメトリック データの間隔 (ウィンドウ サイズ)。</span><span class="sxs-lookup"><span data-stu-id="8c104-108">The interval (window size) for which the metric data was returned in.</span></span>  <span data-ttu-id="8c104-109">これは、後で調整可能性があり、最初に要求内容から返されます。</span><span class="sxs-lookup"><span data-stu-id="8c104-109">This may be adjusted in the future and returned back from what was originally requested.</span></span>  <span data-ttu-id="8c104-110">これがメタデータの要求が行われた場合に存在しません。</span><span class="sxs-lookup"><span data-stu-id="8c104-110">This is not present if a metadata request was made.</span></span></param>
        <summary>
            <span data-ttu-id="8c104-111">応答のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8c104-111">Initializes a new instance of the Response class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cost">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Cost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Cost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Response.Cost" />
      <MemberSignature Language="VB.NET" Value="Public Property Cost As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Cost : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Response.Cost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cost")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c104-112">取得またはデータの場合、クエリのコストを表す整数値を設定します。</span><span class="sxs-lookup"><span data-stu-id="8c104-112">Gets or sets the integer value representing the cost of the query, for data case.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Response.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Interval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Response.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="interval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c104-113">間隔を設定します (ウィンドウ サイズ) で返されたメトリック データを取得またはします。</span><span class="sxs-lookup"><span data-stu-id="8c104-113">Gets or sets the interval (window size) for which the metric data was returned in.</span></span>  <span data-ttu-id="8c104-114">これは、後で調整可能性があり、最初に要求内容から返されます。</span><span class="sxs-lookup"><span data-stu-id="8c104-114">This may be adjusted in the future and returned back from what was originally requested.</span></span>  <span data-ttu-id="8c104-115">これがメタデータの要求が行われた場合に存在しません。</span><span class="sxs-lookup"><span data-stu-id="8c104-115">This is not present if a metadata request was made.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timespan">
      <MemberSignature Language="C#" Value="public string Timespan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Timespan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Response.Timespan" />
      <MemberSignature Language="VB.NET" Value="Public Property Timespan As String" />
      <MemberSignature Language="F#" Value="member this.Timespan : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Response.Timespan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timespan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c104-116">取得またはデータを取得した値を設定します。</span><span class="sxs-lookup"><span data-stu-id="8c104-116">Gets or sets the timespan for which the data was retrieved.</span></span> <span data-ttu-id="8c104-117">その値が連結された 2 つの datatimes から成るで区切られた '/' です。</span><span class="sxs-lookup"><span data-stu-id="8c104-117">Its value consists of two datatimes concatenated, separated by '/'.</span></span>
            <span data-ttu-id="8c104-118">これは、後で調整可能性があり、最初に要求内容から返されます。</span><span class="sxs-lookup"><span data-stu-id="8c104-118">This may be adjusted in the future and returned back from what was originally requested.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Response.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="response.Validate " />
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
            <span data-ttu-id="8c104-119">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8c104-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8c104-120">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8c104-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.Metric&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Response.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of Metric)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Response.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c104-121">取得またはコレクションの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="8c104-121">Gets or sets the value of the collection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>