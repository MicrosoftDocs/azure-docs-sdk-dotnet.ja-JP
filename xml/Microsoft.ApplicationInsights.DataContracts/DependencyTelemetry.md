<Type Name="DependencyTelemetry" FullName="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry">
  <TypeSignature Language="C#" Value="public sealed class DependencyTelemetry : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry, Microsoft.ApplicationInsights.DataContracts.ISupportSampling" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DependencyTelemetry extends Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry implements class Microsoft.ApplicationInsights.Channel.ITelemetry, class Microsoft.ApplicationInsights.DataContracts.ISupportMetrics, class Microsoft.ApplicationInsights.DataContracts.ISupportProperties, class Microsoft.ApplicationInsights.DataContracts.ISupportSampling" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DependencyTelemetry&#xA;Inherits OperationTelemetry&#xA;Implements ISupportSampling" />
  <TypeSignature Language="F#" Value="type DependencyTelemetry = class&#xA;    inherit OperationTelemetry&#xA;    interface ITelemetry&#xA;    interface ISupportProperties&#xA;    interface ISupportSampling&#xA;    interface ISupportMetrics" />
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
            <span data-ttu-id="b9d98-101">収集された依存関係に関する情報を表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="b9d98-101">The class that represents information about the collected dependency.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DependencyTelemetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.#ctor" />
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
            <span data-ttu-id="b9d98-102"><see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-102">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DependencyTelemetry (string dependencyTypeName, string target, string dependencyName, string data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string dependencyTypeName, string target, string dependencyName, string data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dependencyTypeName As String, target As String, dependencyName As String, data As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry : string * string * string * string -&gt; Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" Usage="new Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry (dependencyTypeName, target, dependencyName, data)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dependencyTypeName" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="dependencyName" Type="System.String" />
        <Parameter Name="data" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dependencyTypeName">To be added.</param>
        <param name="target">To be added.</param>
        <param name="dependencyName">To be added.</param>
        <param name="data">To be added.</param>
        <summary>
            <span data-ttu-id="b9d98-103">新しいインスタンスを初期化、<see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" />クラスに、指定された<paramref name="dependencyName" />、 <paramref name="target" />、 <paramref name="dependencyName" />、<paramref name="data" />プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="b9d98-103">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" /> class with the given <paramref name="dependencyName" />, <paramref name="target" />, <paramref name="dependencyName" />, <paramref name="data" /> property values.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DependencyTelemetry (string dependencyName, string data, DateTimeOffset startTime, TimeSpan duration, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string dependencyName, string data, valuetype System.DateTimeOffset startTime, valuetype System.TimeSpan duration, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.#ctor(System.String,System.String,System.DateTimeOffset,System.TimeSpan,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dependencyName As String, data As String, startTime As DateTimeOffset, duration As TimeSpan, success As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry : string * string * DateTimeOffset * TimeSpan * bool -&gt; Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" Usage="new Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry (dependencyName, data, startTime, duration, success)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use other constructors which allows to define dependency call with all the properties.")</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="dependencyName" Type="System.String" />
        <Parameter Name="data" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="duration" Type="System.TimeSpan" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="dependencyName">To be added.</param>
        <param name="data">To be added.</param>
        <param name="startTime">To be added.</param>
        <param name="duration">To be added.</param>
        <param name="success">To be added.</param>
        <summary>
            <span data-ttu-id="b9d98-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" />クラスに、指定された<paramref name="dependencyName" />、 <paramref name="data" />、 <paramref name="startTime" />、<paramref name="duration" />と<paramref name="success" />プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="b9d98-104">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" /> class with the given <paramref name="dependencyName" />, <paramref name="data" />, <paramref name="startTime" />, <paramref name="duration" /> and <paramref name="success" /> property values.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DependencyTelemetry (string dependencyTypeName, string target, string dependencyName, string data, DateTimeOffset startTime, TimeSpan duration, string resultCode, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string dependencyTypeName, string target, string dependencyName, string data, valuetype System.DateTimeOffset startTime, valuetype System.TimeSpan duration, string resultCode, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.#ctor(System.String,System.String,System.String,System.String,System.DateTimeOffset,System.TimeSpan,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dependencyTypeName As String, target As String, dependencyName As String, data As String, startTime As DateTimeOffset, duration As TimeSpan, resultCode As String, success As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry : string * string * string * string * DateTimeOffset * TimeSpan * string * bool -&gt; Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" Usage="new Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry (dependencyTypeName, target, dependencyName, data, startTime, duration, resultCode, success)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dependencyTypeName" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="dependencyName" Type="System.String" />
        <Parameter Name="data" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="duration" Type="System.TimeSpan" />
        <Parameter Name="resultCode" Type="System.String" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="dependencyTypeName">To be added.</param>
        <param name="target">To be added.</param>
        <param name="dependencyName">To be added.</param>
        <param name="data">To be added.</param>
        <param name="startTime">To be added.</param>
        <param name="duration">To be added.</param>
        <param name="resultCode">To be added.</param>
        <param name="success">To be added.</param>
        <summary>
            <span data-ttu-id="b9d98-105">新しいインスタンスを初期化、<see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" />クラスに、指定された<paramref name="dependencyName" />、 <paramref name="target" />、 <paramref name="dependencyName" />、 <paramref name="data" />、 <paramref name="startTime" />、 <paramref name="duration" />、<paramref name="resultCode" />と<paramref name="success" />とプロパティの値。</span><span class="sxs-lookup"><span data-stu-id="b9d98-105">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" /> class with the given <paramref name="dependencyName" />, <paramref name="target" />, <paramref name="dependencyName" />, <paramref name="data" />, <paramref name="startTime" />, <paramref name="duration" />, <paramref name="resultCode" /> and <paramref name="success" /> and  property values.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandName">
      <MemberSignature Language="C#" Value="public string CommandName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.CommandName" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandName As String" />
      <MemberSignature Language="F#" Value="member this.CommandName : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.CommandName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Renamed to Data")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9d98-106">取得または SQL コマンドのテキストを設定または空には適用されません。</span><span class="sxs-lookup"><span data-stu-id="b9d98-106">Gets or sets text of SQL command or empty it not applicable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public override Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Context" />
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
            <span data-ttu-id="b9d98-107">現在の製品利用統計情報項目に関連付けられているコンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-107">Gets the context associated with the current telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public string Data { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Data" />
      <MemberSignature Language="VB.NET" Value="Public Property Data As String" />
      <MemberSignature Language="F#" Value="member this.Data : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Data" />
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
            <span data-ttu-id="b9d98-108">取得または現在の依存関係のインスタンスに関連付けられているデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-108">Gets or sets data associated with the current dependency instance.</span></span> <span data-ttu-id="b9d98-109">SQL の依存関係、http の依存関係の URL の名前/ステートメントのステートメントをコマンドします。</span><span class="sxs-lookup"><span data-stu-id="b9d98-109">Command name/statement statement for SQL dependency, URL for http dependency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public override Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="override this.DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="dependencyTelemetry.DeepClone " />
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
    <Member MemberName="DependencyKind">
      <MemberSignature Language="C#" Value="public string DependencyKind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DependencyKind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.DependencyKind" />
      <MemberSignature Language="VB.NET" Value="Public Property DependencyKind As String" />
      <MemberSignature Language="F#" Value="member this.DependencyKind : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.DependencyKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Use Type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9d98-110">取得または、SQL、HTTP、Azure などのように、依存関係の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-110">Gets or sets the dependency kind, like SQL, HTTP, Azure, etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DependencyTypeName">
      <MemberSignature Language="C#" Value="public string DependencyTypeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DependencyTypeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.DependencyTypeName" />
      <MemberSignature Language="VB.NET" Value="Public Property DependencyTypeName As String" />
      <MemberSignature Language="F#" Value="member this.DependencyTypeName : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.DependencyTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Renamed to Type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b9d98-111">取得または依存関係の種類名を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-111">Gets or sets the dependency type name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Duration">
      <MemberSignature Language="C#" Value="public override TimeSpan Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Duration" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Duration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Duration : TimeSpan with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Duration" />
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
            <span data-ttu-id="b9d98-112">取得または設定、アプリケーション要求の処理にかかった時間のです。</span><span class="sxs-lookup"><span data-stu-id="b9d98-112">Gets or sets the amount of time it took the application to handle the request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public override string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Id" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Id" />
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
            <span data-ttu-id="b9d98-113">取得または設定の依存関係 id です。</span><span class="sxs-lookup"><span data-stu-id="b9d98-113">Gets or sets Dependency ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IDictionary&lt;string,double&gt; Metrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Metrics As IDictionary(Of String, Double)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.Generic.IDictionary&lt;string, double&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Metrics" />
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
            <span data-ttu-id="b9d98-114">アプリケーション定義のイベントのメトリックのディクショナリを取得します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-114">Gets a dictionary of application-defined event metrics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize">
      <MemberSignature Language="C#" Value="void ITelemetry.Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Microsoft#ApplicationInsights#Channel#ITelemetry#Sanitize" />
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
            <span data-ttu-id="b9d98-115">機能では、制約に基づくプロパティです。</span><span class="sxs-lookup"><span data-stu-id="b9d98-115">Sanitizes the properties based on constraints.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage">
      <MemberSignature Language="C#" Value="Nullable&lt;double&gt; Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Microsoft#ApplicationInsights#DataContracts#ISupportSampling#SamplingPercentage" />
      <MemberSignature Language="VB.NET" Value=" Property SamplingPercentage As Nullable(Of Double) Implements ISupportSampling.SamplingPercentage" />
      <MemberSignature Language="F#" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage" />
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
            <span data-ttu-id="b9d98-116">取得または (0 と 100) の間のデータのサンプリング比率を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-116">Gets or sets data sampling percentage (between 0 and 100).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public override string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Name" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Name" />
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
            <span data-ttu-id="b9d98-117">取得またはリソース名を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-117">Gets or sets resource name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Properties" />
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
            <span data-ttu-id="b9d98-118">アプリケーションで定義されたプロパティの名前と値がこのリモート依存関係に関する追加情報を提供するディクショナリを取得します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-118">Gets a dictionary of application-defined property names and values providing additional information about this remote dependency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResultCode">
      <MemberSignature Language="C#" Value="public string ResultCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResultCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.ResultCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ResultCode As String" />
      <MemberSignature Language="F#" Value="member this.ResultCode : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.ResultCode" />
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
            <span data-ttu-id="b9d98-119">取得または設定の結果コード。</span><span class="sxs-lookup"><span data-stu-id="b9d98-119">Gets or sets the Result Code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public override string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Sequence" />
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
            <span data-ttu-id="b9d98-120">取得または製品利用統計情報アイテムの絶対順序を定義する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-120">Gets or sets the value that defines absolute order of the telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="public override Nullable&lt;bool&gt; Success { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Success" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Success" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Success As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Success : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Success" />
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
            <span data-ttu-id="b9d98-121">取得または依存関係の呼び出しが正常に終了したかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-121">Gets or sets a value indicating whether the dependency call was successful or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Target" />
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
            <span data-ttu-id="b9d98-122">取得または依存関係の呼び出しのターゲットを設定します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-122">Gets or sets target of dependency call.</span></span> <span data-ttu-id="b9d98-123">SQL server 名、url のホストなどです。</span><span class="sxs-lookup"><span data-stu-id="b9d98-123">SQL server name, url host, etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public override DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Timestamp" />
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
            <span data-ttu-id="b9d98-124">取得または日付と時刻の製品利用統計情報が記録されるタイミングを設定します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-124">Gets or sets date and time when telemetry was recorded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry.Type" />
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
            <span data-ttu-id="b9d98-125">取得または依存関係の種類名を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9d98-125">Gets or sets the dependency type name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>