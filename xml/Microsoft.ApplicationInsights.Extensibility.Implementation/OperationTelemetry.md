<Type Name="OperationTelemetry" FullName="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry">
  <TypeSignature Language="C#" Value="public abstract class OperationTelemetry : Microsoft.ApplicationInsights.Channel.ITelemetry, Microsoft.ApplicationInsights.DataContracts.ISupportMetrics, Microsoft.ApplicationInsights.DataContracts.ISupportProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit OperationTelemetry extends System.Object implements class Microsoft.ApplicationInsights.Channel.ITelemetry, class Microsoft.ApplicationInsights.DataContracts.ISupportMetrics, class Microsoft.ApplicationInsights.DataContracts.ISupportProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class OperationTelemetry&#xA;Implements ISupportMetrics, ISupportProperties, ITelemetry" />
  <TypeSignature Language="F#" Value="type OperationTelemetry = class&#xA;    interface ITelemetry&#xA;    interface ISupportMetrics&#xA;    interface ISupportProperties" />
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
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d2969-101">製品利用統計情報の種類での期間を表す基本クラスです。</span><span class="sxs-lookup"><span data-stu-id="d2969-101">Base class for telemetry types representing duration in time.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OperationTelemetry ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Context" />
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
            <span data-ttu-id="d2969-102">要求が処理されるときに、アプリケーションに関するコンテキスト情報を格納しているオブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="d2969-102">Gets the object that contains contextual information about the application at the time when it handled the request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="abstract member DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="operationTelemetry.DeepClone " />
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
      <MemberSignature Language="C#" Value="public abstract TimeSpan Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Duration" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Property Duration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Duration : TimeSpan with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Duration" />
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
            <span data-ttu-id="d2969-103">取得または操作の期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="d2969-103">Gets or sets the duration of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public abstract string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Id" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Id" />
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
            <span data-ttu-id="d2969-104">取得または設定操作の id。</span><span class="sxs-lookup"><span data-stu-id="d2969-104">Gets or sets Operation ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public abstract System.Collections.Generic.IDictionary&lt;string,double&gt; Metrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property Metrics As IDictionary(Of String, Double)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.Generic.IDictionary&lt;string, double&gt;" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Metrics" />
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
            <span data-ttu-id="d2969-105">カスタム メトリックのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="d2969-105">Gets the custom metrics collection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize">
      <MemberSignature Language="C#" Value="void ITelemetry.Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Microsoft#ApplicationInsights#Channel#ITelemetry#Sanitize" />
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
            <span data-ttu-id="d2969-106">機能では、制約に基づくプロパティです。</span><span class="sxs-lookup"><span data-stu-id="d2969-106">Sanitizes the properties based on constraints.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public abstract string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Name" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Name" />
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
            <span data-ttu-id="d2969-107">操作の名前を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="d2969-107">Gets or sets the name of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public abstract System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Properties" />
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
            <span data-ttu-id="d2969-108">カスタム プロパティのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="d2969-108">Gets the custom properties collection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sanitize">
      <MemberSignature Language="C#" Value="protected void Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Sanitize" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Sanitize ()" />
      <MemberSignature Language="F#" Value="member this.Sanitize : unit -&gt; unit" Usage="operationTelemetry.Sanitize " />
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
            <span data-ttu-id="d2969-109">メソッドを呼び出す OperationTelemetry.Sanitize 子からクラスを許可します。</span><span class="sxs-lookup"><span data-stu-id="d2969-109">Allow to call OperationTelemetry.Sanitize method from child classes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public abstract string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Sequence" />
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
            <span data-ttu-id="d2969-110">取得または製品利用統計情報アイテムの絶対順序を定義する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="d2969-110">Gets or sets the value that defines absolute order of the telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTimeOffset StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use Timestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d2969-111">取得または操作の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="d2969-111">Gets or sets the start time of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="public abstract Nullable&lt;bool&gt; Success { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Success" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Success" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Property Success As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Success : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Success" />
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
            <span data-ttu-id="d2969-112">取得または操作が正常に完了したかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="d2969-112">Gets or sets whether operation has finished successfully.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public abstract DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry.Timestamp" />
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
            <span data-ttu-id="d2969-113">取得または操作のタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="d2969-113">Gets or sets the timestamp for the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>