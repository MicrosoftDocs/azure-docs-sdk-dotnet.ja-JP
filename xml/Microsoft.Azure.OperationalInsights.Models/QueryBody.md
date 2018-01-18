<Type Name="QueryBody" FullName="Microsoft.Azure.OperationalInsights.Models.QueryBody">
  <TypeSignature Language="C#" Value="public class QueryBody" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueryBody extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.OperationalInsights.Models.QueryBody" />
  <TypeSignature Language="VB.NET" Value="Public Class QueryBody" />
  <TypeSignature Language="F#" Value="type QueryBody = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>0.9.0.1</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dc984-101">分析クエリ。</span><span class="sxs-lookup"><span data-stu-id="dc984-101">The Analytics query.</span></span> <span data-ttu-id="dc984-102">詳細については、[分析クエリの構文](https://azure.microsoft.com/documentation/articles/app-insights-analytics-reference/)</span><span class="sxs-lookup"><span data-stu-id="dc984-102">Learn more about the [Analytics query syntax](https://azure.microsoft.com/documentation/articles/app-insights-analytics-reference/)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueryBody ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.QueryBody.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc984-103">QueryBody クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc984-103">Initializes a new instance of the QueryBody class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueryBody (string query, Nullable&lt;TimeSpan&gt; timespan = null, System.Collections.Generic.IList&lt;string&gt; workspaces = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string query, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timespan, class System.Collections.Generic.IList`1&lt;string&gt; workspaces) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.QueryBody.#ctor(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (query As String, Optional timespan As Nullable(Of TimeSpan) = null, Optional workspaces As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.Models.QueryBody : string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.OperationalInsights.Models.QueryBody" Usage="new Microsoft.Azure.OperationalInsights.Models.QueryBody (query, timespan, workspaces)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="timespan" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="workspaces" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="dc984-104">クエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="dc984-104">The query to execute.</span></span></param>
        <param name="timespan"><span data-ttu-id="dc984-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="dc984-105">Optional.</span></span> <span data-ttu-id="dc984-106">データをクエリする timespan です。</span><span class="sxs-lookup"><span data-stu-id="dc984-106">The timespan over which to query data.</span></span> <span data-ttu-id="dc984-107">これは、ISO8601 時間、期間の値です。</span><span class="sxs-lookup"><span data-stu-id="dc984-107">This is an ISO8601 time period value.</span></span>  <span data-ttu-id="dc984-108">この期間が他にも、クエリ式で指定されている、適用されます。</span><span class="sxs-lookup"><span data-stu-id="dc984-108">This timespan is applied in addition to any that are specified in the query expression.</span></span></param>
        <param name="workspaces"><span data-ttu-id="dc984-109">クエリに含まれているワークスペースの一覧です。</span><span class="sxs-lookup"><span data-stu-id="dc984-109">A list of workspaces that are included in the query.</span></span></param>
        <summary>
            <span data-ttu-id="dc984-110">QueryBody クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc984-110">Initializes a new instance of the QueryBody class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public string Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.QueryBody.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As String" />
      <MemberSignature Language="F#" Value="member this.Query : string with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.QueryBody.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc984-111">取得または実行するクエリを設定します。</span><span class="sxs-lookup"><span data-stu-id="dc984-111">Gets or sets the query to execute.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timespan">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Timespan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Timespan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.QueryBody.Timespan" />
      <MemberSignature Language="VB.NET" Value="Public Property Timespan As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Timespan : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.QueryBody.Timespan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timespan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc984-112">取得または設定オプション。</span><span class="sxs-lookup"><span data-stu-id="dc984-112">Gets or sets optional.</span></span> <span data-ttu-id="dc984-113">データをクエリする timespan です。</span><span class="sxs-lookup"><span data-stu-id="dc984-113">The timespan over which to query data.</span></span> <span data-ttu-id="dc984-114">これは、ISO8601 時間、期間の値です。</span><span class="sxs-lookup"><span data-stu-id="dc984-114">This is an ISO8601 time period value.</span></span>  <span data-ttu-id="dc984-115">この期間が他にも、クエリ式で指定されている、適用されます。</span><span class="sxs-lookup"><span data-stu-id="dc984-115">This timespan is applied in addition to any that are specified in the query expression.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.Models.QueryBody.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="queryBody.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc984-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="dc984-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dc984-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dc984-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Workspaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Workspaces { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Workspaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.Models.QueryBody.Workspaces" />
      <MemberSignature Language="VB.NET" Value="Public Property Workspaces As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Workspaces : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.OperationalInsights.Models.QueryBody.Workspaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workspaces")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc984-118">取得またはクエリに含まれているワークスペースの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="dc984-118">Gets or sets a list of workspaces that are included in the query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>