<Type Name="EventTelemetry" FullName="Microsoft.ApplicationInsights.DataContracts.EventTelemetry">
  <TypeSignature Language="C#" Value="public sealed class EventTelemetry : Microsoft.ApplicationInsights.Channel.ITelemetry, Microsoft.ApplicationInsights.DataContracts.ISupportMetrics, Microsoft.ApplicationInsights.DataContracts.ISupportProperties, Microsoft.ApplicationInsights.DataContracts.ISupportSampling" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventTelemetry extends System.Object implements class Microsoft.ApplicationInsights.Channel.ITelemetry, class Microsoft.ApplicationInsights.DataContracts.ISupportMetrics, class Microsoft.ApplicationInsights.DataContracts.ISupportProperties, class Microsoft.ApplicationInsights.DataContracts.ISupportSampling" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventTelemetry&#xA;Implements ISupportMetrics, ISupportProperties, ISupportSampling, ITelemetry" />
  <TypeSignature Language="F#" Value="type EventTelemetry = class&#xA;    interface ITelemetry&#xA;    interface ISupportProperties&#xA;    interface ISupportSampling&#xA;    interface ISupportMetrics" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.Channel.ITelemetry</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.DataContracts.ISupportMetrics</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.DataContracts.ISupportProperties</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.DataContracts.ISupportSampling</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1eec9-101">テレメトリの種類のイベントを追跡するために使用します。</span><span class="sxs-lookup"><span data-stu-id="1eec9-101">Telemetry type used to track events.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventTelemetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.#ctor" />
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
            <span data-ttu-id="1eec9-102"><see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1eec9-102">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventTelemetry (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.DataContracts.EventTelemetry : string -&gt; Microsoft.ApplicationInsights.DataContracts.EventTelemetry" Usage="new Microsoft.ApplicationInsights.DataContracts.EventTelemetry name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>
            <span data-ttu-id="1eec9-103">新しいインスタンスを初期化、<see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" />クラスに、指定された<paramref name="name" />です。</span><span class="sxs-lookup"><span data-stu-id="1eec9-103">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" /> class with the given <paramref name="name" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="1eec9-104">イベント<paramref name="name" />null または空の文字列です。</span><span class="sxs-lookup"><span data-stu-id="1eec9-104">The event <paramref name="name" /> is null or empty string.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Context" />
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
            <span data-ttu-id="1eec9-105">現在の製品利用統計情報項目に関連付けられているコンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="1eec9-105">Gets the context associated with the current telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="abstract member DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry&#xA;override this.DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="eventTelemetry.DeepClone " />
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
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,double&gt; Metrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metrics As IDictionary(Of String, Double)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.Generic.IDictionary&lt;string, double&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Metrics" />
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
            <span data-ttu-id="1eec9-106">アプリケーション定義のイベントのメトリックのディクショナリを取得します。</span><span class="sxs-lookup"><span data-stu-id="1eec9-106">Gets a dictionary of application-defined event metrics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize">
      <MemberSignature Language="C#" Value="void ITelemetry.Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Microsoft#ApplicationInsights#Channel#ITelemetry#Sanitize" />
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
            <span data-ttu-id="1eec9-107">機能では、制約に基づくプロパティです。</span><span class="sxs-lookup"><span data-stu-id="1eec9-107">Sanitizes the properties based on constraints.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage">
      <MemberSignature Language="C#" Value="Nullable&lt;double&gt; Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Microsoft#ApplicationInsights#DataContracts#ISupportSampling#SamplingPercentage" />
      <MemberSignature Language="VB.NET" Value=" Property SamplingPercentage As Nullable(Of Double) Implements ISupportSampling.SamplingPercentage" />
      <MemberSignature Language="F#" Usage="Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage" />
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
            <span data-ttu-id="1eec9-108">取得または (0 と 100) の間のデータのサンプリング比率を設定します。</span><span class="sxs-lookup"><span data-stu-id="1eec9-108">Gets or sets data sampling percentage (between 0 and 100).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Name" />
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
            <span data-ttu-id="1eec9-109">取得またはイベントの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1eec9-109">Gets or sets the name of the event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Properties" />
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
            <span data-ttu-id="1eec9-110">アプリケーションで定義されたプロパティの名前と値がこのイベントに関する追加情報を提供するディクショナリを取得します。</span><span class="sxs-lookup"><span data-stu-id="1eec9-110">Gets a dictionary of application-defined property names and values providing additional information about this event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Sequence" />
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
            <span data-ttu-id="1eec9-111">取得または製品利用統計情報アイテムの絶対順序を定義する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="1eec9-111">Gets or sets the value that defines absolute order of the telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.EventTelemetry.Timestamp" />
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
            <span data-ttu-id="1eec9-112">取得またはイベントが記録されたときの日時を設定します。</span><span class="sxs-lookup"><span data-stu-id="1eec9-112">Gets or sets date and time when event was recorded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>