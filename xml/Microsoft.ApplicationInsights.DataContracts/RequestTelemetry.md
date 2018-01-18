<Type Name="RequestTelemetry" FullName="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry">
  <TypeSignature Language="C#" Value="public sealed class RequestTelemetry : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry, Microsoft.ApplicationInsights.DataContracts.ISupportSampling" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RequestTelemetry extends Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry implements class Microsoft.ApplicationInsights.Channel.ITelemetry, class Microsoft.ApplicationInsights.DataContracts.ISupportMetrics, class Microsoft.ApplicationInsights.DataContracts.ISupportProperties, class Microsoft.ApplicationInsights.DataContracts.ISupportSampling" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RequestTelemetry&#xA;Inherits OperationTelemetry&#xA;Implements ISupportSampling" />
  <TypeSignature Language="F#" Value="type RequestTelemetry = class&#xA;    inherit OperationTelemetry&#xA;    interface ITelemetry&#xA;    interface ISupportProperties&#xA;    interface ISupportMetrics&#xA;    interface ISupportSampling" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.DataContracts.ISupportSampling</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f8358-101">Web 要求がアプリケーションによって処理に関する情報をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="f8358-101">Encapsulates information about a web request handled by the application.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="f8358-102">インスタンスを渡すことによって、web アプリケーションに Application Insights によって処理された要求に関する情報を送信することができます、<see cref="T:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" />クラスを<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackRequest(Microsoft.ApplicationInsights.DataContracts.RequestTelemetry)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="f8358-102">You can send information about requests processed by your web application to Application Insights by passing an instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" /> class to the <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackRequest(Microsoft.ApplicationInsights.DataContracts.RequestTelemetry)" /> method.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestTelemetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8358-103"><see cref="T:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f8358-103">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestTelemetry (string name, DateTimeOffset startTime, TimeSpan duration, string responseCode, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.DateTimeOffset startTime, valuetype System.TimeSpan duration, string responseCode, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.#ctor(System.String,System.DateTimeOffset,System.TimeSpan,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, startTime As DateTimeOffset, duration As TimeSpan, responseCode As String, success As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.DataContracts.RequestTelemetry : string * DateTimeOffset * TimeSpan * string * bool -&gt; Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" Usage="new Microsoft.ApplicationInsights.DataContracts.RequestTelemetry (name, startTime, duration, responseCode, success)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="duration" Type="System.TimeSpan" />
        <Parameter Name="responseCode" Type="System.String" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="startTime">To be added.</param>
        <param name="duration">To be added.</param>
        <param name="responseCode">To be added.</param>
        <param name="success">To be added.</param>
        <summary>
            <span data-ttu-id="f8358-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" />クラスに、指定された<paramref name="name" />、 <paramref name="startTime" />、 <paramref name="duration" />、<paramref name="responseCode" />と<paramref name="success" />プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="f8358-104">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" /> class with the given <paramref name="name" />, <paramref name="startTime" />, <paramref name="duration" />, <paramref name="responseCode" /> and <paramref name="success" /> property values.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public override Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Context" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Context</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.TelemetryContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-105">要求が処理されるときに、アプリケーションに関するコンテキスト情報を格納しているオブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="f8358-105">Gets the object that contains contextual information about the application at the time when it handled the request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public override Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="override this.DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="requestTelemetry.DeepClone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetry.DeepClone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Channel.ITelemetry</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Duration">
      <MemberSignature Language="C#" Value="public override TimeSpan Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Duration" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Duration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Duration : TimeSpan with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Duration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-106">取得または設定、アプリケーション要求の処理にかかった時間のです。</span><span class="sxs-lookup"><span data-stu-id="f8358-106">Gets or sets the amount of time it took the application to handle the request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpMethod">
      <MemberSignature Language="C#" Value="public string HttpMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HttpMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.HttpMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpMethod As String" />
      <MemberSignature Language="F#" Value="member this.HttpMethod : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.HttpMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Include http verb into request telemetry name and use custom properties to report http method as a dimension.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-107">取得または要求の HTTP メソッドを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8358-107">Gets or sets the HTTP method of the request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public override string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Id" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>  
            <span data-ttu-id="f8358-108">取得または設定要求 id です。</span><span class="sxs-lookup"><span data-stu-id="f8358-108">Gets or sets Request ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IDictionary&lt;string,double&gt; Metrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Metrics As IDictionary(Of String, Double)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.Generic.IDictionary&lt;string, double&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Metrics" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.DataContracts.ISupportMetrics.Metrics</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-109">アプリケーション定義の要求のメトリックのディクショナリを取得します。</span><span class="sxs-lookup"><span data-stu-id="f8358-109">Gets a dictionary of application-defined request metrics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize">
      <MemberSignature Language="C#" Value="void ITelemetry.Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Microsoft#ApplicationInsights#Channel#ITelemetry#Sanitize" />
      <MemberSignature Language="VB.NET" Value="Sub Sanitize () Implements ITelemetry.Sanitize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8358-110">機能では、制約に基づくプロパティです。</span><span class="sxs-lookup"><span data-stu-id="f8358-110">Sanitizes the properties based on constraints.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage">
      <MemberSignature Language="C#" Value="Nullable&lt;double&gt; Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Microsoft#ApplicationInsights#DataContracts#ISupportSampling#SamplingPercentage" />
      <MemberSignature Language="VB.NET" Value=" Property SamplingPercentage As Nullable(Of Double) Implements ISupportSampling.SamplingPercentage" />
      <MemberSignature Language="F#" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-111">取得または (0 と 100) の間のデータのサンプリング比率を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8358-111">Gets or sets data sampling percentage (between 0 and 100).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public override string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Name" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-112">取得または要求されたページの人間が判読できる名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8358-112">Gets or sets human-readable name of the requested page.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Properties" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.DataContracts.ISupportProperties.Properties</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-113">アプリケーションで定義されたプロパティの名前と値がこの要求に関する追加情報を提供するディクショナリを取得します。</span><span class="sxs-lookup"><span data-stu-id="f8358-113">Gets a dictionary of application-defined property names and values providing additional information about this request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseCode">
      <MemberSignature Language="C#" Value="public string ResponseCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResponseCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.ResponseCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ResponseCode As String" />
      <MemberSignature Language="F#" Value="member this.ResponseCode : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.ResponseCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-114">取得または要求を処理した後で、アプリケーションによって返される応答コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8358-114">Gets or sets response code returned by the application after handling the request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public override string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Sequence" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-115">取得または製品利用統計情報アイテムの絶対順序を定義する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8358-115">Gets or sets the value that defines absolute order of the telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-116">取得または要求テレメトリ オブジェクトのソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8358-116">Gets or sets the source for the request telemetry object.</span></span> <span data-ttu-id="f8358-117">これは多くの場合は、呼び出し元を識別するハッシュされたインストルメンテーション キーです。</span><span class="sxs-lookup"><span data-stu-id="f8358-117">This often is a hashed instrumentation key identifying the caller.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="public override Nullable&lt;bool&gt; Success { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Success" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Success" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Success As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Success : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Success" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-118">取得またはアプリケーションが正常に要求を処理するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8358-118">Gets or sets a value indicating whether application handled the request successfully.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public override DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Timestamp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-119">取得または日付と時刻の製品利用統計情報が記録されるタイミングを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8358-119">Gets or sets date and time when telemetry was recorded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public Uri Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As Uri" />
      <MemberSignature Language="F#" Value="member this.Url : Uri with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8358-120">取得または設定は、url (省略可能) を要求します。</span><span class="sxs-lookup"><span data-stu-id="f8358-120">Gets or sets request url (optional).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>