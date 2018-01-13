<Type Name="TelemetryClient" FullName="Microsoft.ApplicationInsights.TelemetryClient">
  <TypeSignature Language="C#" Value="public sealed class TelemetryClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TelemetryClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.TelemetryClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TelemetryClient" />
  <TypeSignature Language="F#" Value="type TelemetryClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            イベント、メトリック、およびその他のテレメトリを Application Insights サービスに送信します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.#ctor" />
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
            <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> クラスの新しいインスタンスを初期化します。 アクティブな構成で、ApplicationInsights.config から読み込まれた通常テレメトリを送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryClient (Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.#ctor(Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configuration As TelemetryConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.TelemetryClient : Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration -&gt; Microsoft.ApplicationInsights.TelemetryClient" Usage="new Microsoft.ApplicationInsights.TelemetryClient configuration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configuration" Type="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />
      </Parameters>
      <Docs>
        <param name="configuration">To be added.</param>
        <summary>
            <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> クラスの新しいインスタンスを初期化します。 指定した製品利用統計情報を送信<paramref name="configuration" />です。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><paramref name="configuration" />が null です。</exception>
        <exception cref="T:System.ArgumentException"><paramref name="configuration" />製品利用統計情報のチャネルがありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.TelemetryClient.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.TelemetryClient.Context" />
      <MemberType>Property</MemberType>
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
            テレメトリを送信するを拡張するために使用される現在のコンテキストを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public void Flush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Flush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.Flush" />
      <MemberSignature Language="VB.NET" Value="Public Sub Flush ()" />
      <MemberSignature Language="F#" Value="member this.Flush : unit -&gt; unit" Usage="telemetryClient.Flush " />
      <MemberType>Method</MemberType>
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
            メモリ内のバッファーをフラッシュします。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (Microsoft.ApplicationInsights.Channel.ITelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Initialize(class Microsoft.ApplicationInsights.Channel.ITelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.Initialize(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (telemetry As ITelemetry)" />
      <MemberSignature Language="F#" Value="member this.Initialize : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="telemetryClient.Initialize telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">初期化するために製品利用統計情報項目。</param>
        <summary>
            このメソッドは、Application Insights のインフラストラクチャの内部部分です。 呼び出す必要はありません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstrumentationKey">
      <MemberSignature Language="C#" Value="public string InstrumentationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstrumentationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.TelemetryClient.InstrumentationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property InstrumentationKey As String" />
      <MemberSignature Language="F#" Value="member this.InstrumentationKey : string with get, set" Usage="Microsoft.ApplicationInsights.TelemetryClient.InstrumentationKey" />
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
            すべての既定のインストルメンテーション キーを設定を取得または<see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" />オブジェクトがこの記録<see cref="T:Microsoft.ApplicationInsights.TelemetryClient" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsEnabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Function IsEnabled () As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : unit -&gt; bool" Usage="telemetryClient.IsEnabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            追跡が有効かどうかを判断することを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Track">
      <MemberSignature Language="C#" Value="public void Track (Microsoft.ApplicationInsights.Channel.ITelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Track(class Microsoft.ApplicationInsights.Channel.ITelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.Track(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Track (telemetry As ITelemetry)" />
      <MemberSignature Language="F#" Value="member this.Track : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="telemetryClient.Track telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            このメソッドは、Application Insights のインフラストラクチャの内部部分です。 呼び出す必要はありません。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackAvailability">
      <MemberSignature Language="C#" Value="public void TrackAvailability (Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackAvailability(class Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackAvailability(Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackAvailability (telemetry As AvailabilityTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackAvailability : Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry -&gt; unit" Usage="telemetryClient.TrackAvailability telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            アプリケーションの可用性に関する情報を送信します。
            ごとに別々<see cref="T:Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry" />呼び出しごとにインスタンス<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackAvailability(Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry)" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackAvailability">
      <MemberSignature Language="C#" Value="public void TrackAvailability (string name, DateTimeOffset timeStamp, TimeSpan duration, string runLocation, bool success, string message = null, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null, System.Collections.Generic.IDictionary&lt;string,double&gt; metrics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackAvailability(string name, valuetype System.DateTimeOffset timeStamp, valuetype System.TimeSpan duration, string runLocation, bool success, string message, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackAvailability(System.String,System.DateTimeOffset,System.TimeSpan,System.String,System.Boolean,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackAvailability (name As String, timeStamp As DateTimeOffset, duration As TimeSpan, runLocation As String, success As Boolean, Optional message As String = null, Optional properties As IDictionary(Of String, String) = null, Optional metrics As IDictionary(Of String, Double) = null)" />
      <MemberSignature Language="F#" Value="member this.TrackAvailability : string * DateTimeOffset * TimeSpan * string * bool * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, double&gt; -&gt; unit" Usage="telemetryClient.TrackAvailability (name, timeStamp, duration, runLocation, success, message, properties, metrics)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeStamp" Type="System.DateTimeOffset" />
        <Parameter Name="duration" Type="System.TimeSpan" />
        <Parameter Name="runLocation" Type="System.String" />
        <Parameter Name="success" Type="System.Boolean" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="name">可用性テストの名前。</param>
        <param name="timeStamp">可用性がキャプチャされた時間です。</param>
        <param name="duration">可用性テストを実行にかかった時間です。</param>
        <param name="runLocation">可用性テストの実行場所の名前。</param>
        <param name="success">可用性テストが正常に実行された場合は true。</param>
        <param name="message">可用性テストの実行が失敗のエラー メッセージ。</param>
        <param name="properties">この可用性利用統計情報を分類し、検索に使用できる名前付き文字列値です。</param>
        <param name="metrics">この可用性製品利用統計情報に関連付けられている追加の値。</param>
        <summary>
            アプリケーションの可用性に関する情報を送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackDependency">
      <MemberSignature Language="C#" Value="public void TrackDependency (Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackDependency(class Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackDependency(Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackDependency (telemetry As DependencyTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackDependency : Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry -&gt; unit" Usage="telemetryClient.TrackDependency telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            アプリケーションの外部の依存関係の呼び出しに関する情報を送信します。
            ごとに別々<see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" />呼び出しごとにインスタンス<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackDependency(Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry)" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackDependency">
      <MemberSignature Language="C#" Value="public void TrackDependency (string dependencyName, string commandName, DateTimeOffset startTime, TimeSpan duration, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackDependency(string dependencyName, string commandName, valuetype System.DateTimeOffset startTime, valuetype System.TimeSpan duration, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackDependency(System.String,System.String,System.DateTimeOffset,System.TimeSpan,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackDependency (dependencyName As String, commandName As String, startTime As DateTimeOffset, duration As TimeSpan, success As Boolean)" />
      <MemberSignature Language="F#" Value="member this.TrackDependency : string * string * DateTimeOffset * TimeSpan * bool -&gt; unit" Usage="telemetryClient.TrackDependency (dependencyName, commandName, startTime, duration, success)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dependencyName" Type="System.String" />
        <Parameter Name="commandName" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="duration" Type="System.TimeSpan" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="dependencyName">外部の依存関係の名前です。</param>
        <param name="commandName">依存関係呼び出しコマンドの名前。</param>
        <param name="startTime">依存関係が呼び出された時刻。</param>
        <param name="duration">外部の依存関係が呼び出しを処理に要した時間。</param>
        <param name="success">依存関係の呼び出しが正常に処理された場合は true。</param>
        <summary>
            アプリケーションの外部の依存関係の呼び出しに関する情報を送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackDependency">
      <MemberSignature Language="C#" Value="public void TrackDependency (string dependencyTypeName, string target, string dependencyName, string data, DateTimeOffset startTime, TimeSpan duration, string resultCode, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackDependency(string dependencyTypeName, string target, string dependencyName, string data, valuetype System.DateTimeOffset startTime, valuetype System.TimeSpan duration, string resultCode, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackDependency(System.String,System.String,System.String,System.String,System.DateTimeOffset,System.TimeSpan,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackDependency (dependencyTypeName As String, target As String, dependencyName As String, data As String, startTime As DateTimeOffset, duration As TimeSpan, resultCode As String, success As Boolean)" />
      <MemberSignature Language="F#" Value="member this.TrackDependency : string * string * string * string * DateTimeOffset * TimeSpan * string * bool -&gt; unit" Usage="telemetryClient.TrackDependency (dependencyTypeName, target, dependencyName, data, startTime, duration, resultCode, success)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
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
        <param name="dependencyTypeName">外部の依存関係の種類。</param>
        <param name="target">外部の依存関係のターゲットです。</param>
        <param name="dependencyName">外部の依存関係の名前です。</param>
        <param name="data">依存関係呼び出しコマンドの名前。</param>
        <param name="startTime">依存関係が呼び出された時刻。</param>
        <param name="duration">外部の依存関係が呼び出しを処理に要した時間。</param>
        <param name="resultCode">依存関係の呼び出しの実行の結果コード。</param>
        <param name="success">依存関係の呼び出しが正常に処理された場合は true。</param>
        <summary>
            アプリケーションの外部の依存関係の呼び出しに関する情報を送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackEvent">
      <MemberSignature Language="C#" Value="public void TrackEvent (Microsoft.ApplicationInsights.DataContracts.EventTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackEvent(class Microsoft.ApplicationInsights.DataContracts.EventTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackEvent(Microsoft.ApplicationInsights.DataContracts.EventTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackEvent (telemetry As EventTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackEvent : Microsoft.ApplicationInsights.DataContracts.EventTelemetry -&gt; unit" Usage="telemetryClient.TrackEvent telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.EventTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">イベント ログの項目です。</param>
        <summary>
            送信、<see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" />診断の検索とメトリックス エクスプ ローラーでの集計内に表示します。
            ごとに別々<see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" />呼び出しごとにインスタンス<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackEvent(Microsoft.ApplicationInsights.DataContracts.EventTelemetry)" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackEvent">
      <MemberSignature Language="C#" Value="public void TrackEvent (string eventName, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null, System.Collections.Generic.IDictionary&lt;string,double&gt; metrics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackEvent(string eventName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackEvent(System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackEvent (eventName As String, Optional properties As IDictionary(Of String, String) = null, Optional metrics As IDictionary(Of String, Double) = null)" />
      <MemberSignature Language="F#" Value="member this.TrackEvent : string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, double&gt; -&gt; unit" Usage="telemetryClient.TrackEvent (eventName, properties, metrics)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventName" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="eventName">イベントの名前。</param>
        <param name="properties">検索し、イベントの分類に使用できる名前付き文字列値です。</param>
        <param name="metrics">このイベントに関連付けられている値。</param>
        <summary>
            送信、<see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" />診断の検索とメトリックス エクスプ ローラーでの集計内に表示します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackException">
      <MemberSignature Language="C#" Value="public void TrackException (Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackException(class Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackException(Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackException (telemetry As ExceptionTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackException : Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry -&gt; unit" Usage="telemetryClient.TrackException telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            送信、<see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" />診断検索での表示にします。
            ごとに別々<see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" />呼び出しごとにインスタンス<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackException(Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry)" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackException">
      <MemberSignature Language="C#" Value="public void TrackException (Exception exception, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null, System.Collections.Generic.IDictionary&lt;string,double&gt; metrics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackException(class System.Exception exception, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackException(System.Exception,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.Double})" />
      <MemberSignature Language="F#" Value="member this.TrackException : Exception * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, double&gt; -&gt; unit" Usage="telemetryClient.TrackException (exception, properties, metrics)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="exception">ログに記録される例外。</param>
        <param name="properties">この例外を分類し、検索に使用できる名前付き文字列値です。</param>
        <param name="metrics">この例外に関連付けられている追加の値。</param>
        <summary>
            送信、<see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" />診断検索での表示にします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackMetric">
      <MemberSignature Language="C#" Value="public void TrackMetric (Microsoft.ApplicationInsights.DataContracts.MetricTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackMetric(class Microsoft.ApplicationInsights.DataContracts.MetricTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackMetric(Microsoft.ApplicationInsights.DataContracts.MetricTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackMetric (telemetry As MetricTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackMetric : Microsoft.ApplicationInsights.DataContracts.MetricTelemetry -&gt; unit" Usage="telemetryClient.TrackMetric telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            送信、<see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" />集計されたメトリック データを表すためです。
            ごとに別々<see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" />呼び出しごとにインスタンス<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackMetric(Microsoft.ApplicationInsights.DataContracts.MetricTelemetry)" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackMetric">
      <MemberSignature Language="C#" Value="public void TrackMetric (string name, double value, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackMetric(string name, float64 value, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackMetric(System.String,System.Double,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackMetric (name As String, value As Double, Optional properties As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="member this.TrackMetric : string * double * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="telemetryClient.TrackMetric (name, value, properties)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name">メトリックの名前です。</param>
        <param name="value">メトリックの値。</param>
        <param name="properties">分類とメトリックをフィルター処理に使用できる文字列値の名前です。</param>
        <summary>
            送信、<see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" />メトリック エクスプ ローラーで集計します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackPageView">
      <MemberSignature Language="C#" Value="public void TrackPageView (Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackPageView(class Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackPageView(Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackPageView (telemetry As PageViewTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackPageView : Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry -&gt; unit" Usage="telemetryClient.TrackPageView telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            アプリケーションで表示 ページに関する情報を送信します。
            ごとに別々<see cref="T:Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry" />呼び出しごとにインスタンス<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackPageView(Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry)" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackPageView">
      <MemberSignature Language="C#" Value="public void TrackPageView (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackPageView(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackPageView(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackPageView (name As String)" />
      <MemberSignature Language="F#" Value="member this.TrackPageView : string -&gt; unit" Usage="telemetryClient.TrackPageView name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">ページの名前です。</param>
        <summary>
            アプリケーションで表示 ページに関する情報を送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackRequest">
      <MemberSignature Language="C#" Value="public void TrackRequest (Microsoft.ApplicationInsights.DataContracts.RequestTelemetry request);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackRequest(class Microsoft.ApplicationInsights.DataContracts.RequestTelemetry request) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackRequest(Microsoft.ApplicationInsights.DataContracts.RequestTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackRequest (request As RequestTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackRequest : Microsoft.ApplicationInsights.DataContracts.RequestTelemetry -&gt; unit" Usage="telemetryClient.TrackRequest request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" />
      </Parameters>
      <Docs>
        <param name="request">To be added.</param>
        <summary>
            アプリケーションで処理される要求に関する情報を送信します。
            ごとに別々<see cref="T:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" />呼び出しごとにインスタンス<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackRequest(Microsoft.ApplicationInsights.DataContracts.RequestTelemetry)" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackRequest">
      <MemberSignature Language="C#" Value="public void TrackRequest (string name, DateTimeOffset startTime, TimeSpan duration, string responseCode, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackRequest(string name, valuetype System.DateTimeOffset startTime, valuetype System.TimeSpan duration, string responseCode, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackRequest(System.String,System.DateTimeOffset,System.TimeSpan,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackRequest (name As String, startTime As DateTimeOffset, duration As TimeSpan, responseCode As String, success As Boolean)" />
      <MemberSignature Language="F#" Value="member this.TrackRequest : string * DateTimeOffset * TimeSpan * string * bool -&gt; unit" Usage="telemetryClient.TrackRequest (name, startTime, duration, responseCode, success)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="duration" Type="System.TimeSpan" />
        <Parameter Name="responseCode" Type="System.String" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">要求の名前です。</param>
        <param name="startTime">ページが要求された時間です。</param>
        <param name="duration">要求を処理するアプリケーションによって使用された時間。</param>
        <param name="responseCode">応答ステータス コード。</param>
        <param name="success">アプリケーションによって要求が正常に処理された場合は true。</param>
        <summary>
            アプリケーションで処理される要求に関する情報を送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackTrace">
      <MemberSignature Language="C#" Value="public void TrackTrace (Microsoft.ApplicationInsights.DataContracts.TraceTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackTrace(class Microsoft.ApplicationInsights.DataContracts.TraceTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(Microsoft.ApplicationInsights.DataContracts.TraceTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackTrace (telemetry As TraceTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackTrace : Microsoft.ApplicationInsights.DataContracts.TraceTelemetry -&gt; unit" Usage="telemetryClient.TrackTrace telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.TraceTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">省略可能なプロパティを持つメッセージです。</param>
        <summary>
            診断の検索で表示するためのトレース メッセージを送信します。
            ごとに別々<see cref="T:Microsoft.ApplicationInsights.DataContracts.TraceTelemetry" />呼び出しごとにインスタンス<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(Microsoft.ApplicationInsights.DataContracts.TraceTelemetry)" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackTrace">
      <MemberSignature Language="C#" Value="public void TrackTrace (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackTrace(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackTrace (message As String)" />
      <MemberSignature Language="F#" Value="member this.TrackTrace : string -&gt; unit" Usage="telemetryClient.TrackTrace message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">表示するメッセージ。</param>
        <summary>
            診断の検索で表示するためのトレース メッセージを送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackTrace">
      <MemberSignature Language="C#" Value="public void TrackTrace (string message, Microsoft.ApplicationInsights.DataContracts.SeverityLevel severityLevel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackTrace(string message, valuetype Microsoft.ApplicationInsights.DataContracts.SeverityLevel severityLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(System.String,Microsoft.ApplicationInsights.DataContracts.SeverityLevel)" />
      <MemberSignature Language="F#" Value="member this.TrackTrace : string * Microsoft.ApplicationInsights.DataContracts.SeverityLevel -&gt; unit" Usage="telemetryClient.TrackTrace (message, severityLevel)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="severityLevel" Type="Microsoft.ApplicationInsights.DataContracts.SeverityLevel" />
      </Parameters>
      <Docs>
        <param name="message">表示するメッセージ。</param>
        <param name="severityLevel">重大度レベル。</param>
        <summary>
            診断の検索で表示するためのトレース メッセージを送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackTrace">
      <MemberSignature Language="C#" Value="public void TrackTrace (string message, System.Collections.Generic.IDictionary&lt;string,string&gt; properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackTrace(string message, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackTrace (message As String, properties As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="member this.TrackTrace : string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="telemetryClient.TrackTrace (message, properties)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="message">表示するメッセージ。</param>
        <param name="properties">検索し、イベントの分類に使用できる名前付き文字列値です。</param>
        <summary>
            診断の検索で表示するためのトレース メッセージを送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackTrace">
      <MemberSignature Language="C#" Value="public void TrackTrace (string message, Microsoft.ApplicationInsights.DataContracts.SeverityLevel severityLevel, System.Collections.Generic.IDictionary&lt;string,string&gt; properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackTrace(string message, valuetype Microsoft.ApplicationInsights.DataContracts.SeverityLevel severityLevel, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(System.String,Microsoft.ApplicationInsights.DataContracts.SeverityLevel,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="F#" Value="member this.TrackTrace : string * Microsoft.ApplicationInsights.DataContracts.SeverityLevel * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="telemetryClient.TrackTrace (message, severityLevel, properties)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="severityLevel" Type="Microsoft.ApplicationInsights.DataContracts.SeverityLevel" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="message">表示するメッセージ。</param>
        <param name="severityLevel">重大度レベル。</param>
        <param name="properties">検索し、イベントの分類に使用できる名前付き文字列値です。</param>
        <summary>
            診断の検索で表示するためのトレース メッセージを送信します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>