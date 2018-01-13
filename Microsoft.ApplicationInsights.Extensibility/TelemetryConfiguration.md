<Type Name="TelemetryConfiguration" FullName="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration">
  <TypeSignature Language="C#" Value="public sealed class TelemetryConfiguration : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TelemetryConfiguration extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TelemetryConfiguration&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type TelemetryConfiguration = class&#xA;    interface IDisposable" />
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
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            通常、ApplicationInsights.config ファイルから読み込まれたグローバル遠隔測定の構成をカプセル化します。
            </summary>
    <remarks>
            すべて<see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />オブジェクトの初期化を使用して、<see cref="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Active" />このクラスによって提供される製品利用統計情報の構成。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
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
      <Parameters />
      <Docs>
        <summary>
            TelemetryConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryConfiguration (string instrumentationKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string instrumentationKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (instrumentationKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration : string -&gt; Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" Usage="new Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration instrumentationKey" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="instrumentationKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="instrumentationKey">インストルメンテーション キーは、この構成のインスタンスが提供されます。</param>
        <summary>
            TelemetryConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryConfiguration (string instrumentationKey, Microsoft.ApplicationInsights.Channel.ITelemetryChannel channel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string instrumentationKey, class Microsoft.ApplicationInsights.Channel.ITelemetryChannel channel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.#ctor(System.String,Microsoft.ApplicationInsights.Channel.ITelemetryChannel)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (instrumentationKey As String, channel As ITelemetryChannel)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration : string * Microsoft.ApplicationInsights.Channel.ITelemetryChannel -&gt; Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" Usage="new Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration (instrumentationKey, channel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="instrumentationKey" Type="System.String" />
        <Parameter Name="channel" Type="Microsoft.ApplicationInsights.Channel.ITelemetryChannel" />
      </Parameters>
      <Docs>
        <param name="instrumentationKey">インストルメンテーション キーは、この構成のインスタンスが提供されます。</param>
        <param name="channel">この構成のインスタンスに提供する製品利用統計情報のチャネル。</param>
        <summary>
            TelemetryConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration Active { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration Active" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Active" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Active As TelemetryConfiguration" />
      <MemberSignature Language="F#" Value="member this.Active : Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Active" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アクティブな取得<see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />ApplicationInsights.config ファイルから読み込まれたインスタンス。 構成ファイルが存在しない場合は、アクティブな構成のインスタンスに Application Insights テレメトリを送信するために必要な最小の既定値で初期化されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDefault">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration CreateDefault ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration CreateDefault() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.CreateDefault" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDefault () As TelemetryConfiguration" />
      <MemberSignature Language="F#" Value="static member CreateDefault : unit -&gt; Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.CreateDefault " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            新たに作成<see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />ApplicationInsights.config ファイルからインスタンスが読み込まれます。
            構成ファイルが存在しない場合、構成の新しいインスタンスは、Application Insights にテレメトリを送信するために必要な最小の既定値で初期化されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConfiguration">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration CreateFromConfiguration (string config);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration CreateFromConfiguration(string config) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.CreateFromConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConfiguration (config As String) As TelemetryConfiguration" />
      <MemberSignature Language="F#" Value="static member CreateFromConfiguration : string -&gt; Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.CreateFromConfiguration config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="config">Xml には、構成がシリアル化されます。</param>
        <summary>
            新たに作成<see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />インスタンスが指定された構成から読み込まれます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">構成値が null または空の場合にスローします。</exception>
      </Docs>
    </Member>
    <Member MemberName="DefaultTelemetrySink">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.TelemetrySink DefaultTelemetrySink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.TelemetrySink DefaultTelemetrySink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.DefaultTelemetrySink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultTelemetrySink As TelemetrySink" />
      <MemberSignature Language="F#" Value="member this.DefaultTelemetrySink : Microsoft.ApplicationInsights.Extensibility.TelemetrySink" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.DefaultTelemetrySink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.TelemetrySink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableTelemetry">
      <MemberSignature Language="C#" Value="public bool DisableTelemetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableTelemetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.DisableTelemetry" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableTelemetry As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableTelemetry : bool with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.DisableTelemetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Application Insights への製品利用統計情報の送信が無効になっているかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            すべてで、既定で使用されるこの無効化が設定値を追跡<see cref="T:Microsoft.ApplicationInsights.TelemetryClient" />アプリケーションで作成されたインスタンスです。 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="telemetryConfiguration.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
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
            <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> クラスの現在のインスタンスによって使用されているリソースを解放します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstrumentationKey">
      <MemberSignature Language="C#" Value="public string InstrumentationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstrumentationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.InstrumentationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property InstrumentationKey As String" />
      <MemberSignature Language="F#" Value="member this.InstrumentationKey : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.InstrumentationKey" />
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
            取得またはアプリケーションの既定のインストルメンテーション キーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定ではすべてこのインストルメンテーション キーの値が使用される<see cref="T:Microsoft.ApplicationInsights.TelemetryClient" />アプリケーションで作成されたインスタンスです。 この値は、設定によって上書きされること、<see cref="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.InstrumentationKey" />のプロパティ、<see cref="P:Microsoft.ApplicationInsights.TelemetryClient.Context" />です。
            </remarks>
        <exception cref="T:System.ArgumentNullException">新しい値が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="TelemetryChannel">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Channel.ITelemetryChannel TelemetryChannel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Channel.ITelemetryChannel TelemetryChannel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryChannel" />
      <MemberSignature Language="VB.NET" Value="Public Property TelemetryChannel As ITelemetryChannel" />
      <MemberSignature Language="F#" Value="member this.TelemetryChannel : Microsoft.ApplicationInsights.Channel.ITelemetryChannel with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryChannel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Channel.ITelemetryChannel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または製品利用統計情報のチャネルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TelemetryInitializers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer&gt; TelemetryInitializers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer&gt; TelemetryInitializers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryInitializers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TelemetryInitializers As IList(Of ITelemetryInitializer)" />
      <MemberSignature Language="F#" Value="member this.TelemetryInitializers : System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer&gt;" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryInitializers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一覧を取得<see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" />製品利用統計情報に関する追加情報を提供するオブジェクト。
            </summary>
        <value>To be added.</value>
        <remarks>
            製品利用統計情報の初期化子では、Application Insights テレメトリ コレクションを拡張個人に関する追加情報を指定することによって<see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" />項目など、<see cref="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp" />です。 A<see cref="T:Microsoft.ApplicationInsights.TelemetryClient" />たびに製品利用統計情報の初期化子を呼び出す<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.Track(Microsoft.ApplicationInsights.Channel.ITelemetry)" />メソッドが呼び出されます。
            テレメトリの初期化子の既定のリストが、Application Insights NuGet パッケージによって提供され、アプリケーションのディレクトリに ApplicationInsights.config ファイルから読み込まれます。 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TelemetryProcessorChainBuilder">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder TelemetryProcessorChainBuilder { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder TelemetryProcessorChainBuilder" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryProcessorChainBuilder" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TelemetryProcessorChainBuilder As TelemetryProcessorChainBuilder" />
      <MemberSignature Language="F#" Value="member this.TelemetryProcessorChainBuilder : Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryProcessorChainBuilder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ビルドされ、設定で、TelemetryConfiguration TelemetryProcessors TelemetryProcessorChainBuilder を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TelemetryProcessors">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt; TelemetryProcessors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt; TelemetryProcessors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryProcessors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TelemetryProcessors As ReadOnlyCollection(Of ITelemetryProcessor)" />
      <MemberSignature Language="F#" Value="member this.TelemetryProcessors : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt;" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryProcessors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            TelemetryProcessors の読み取り専用コレクションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TelemetrySinks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.TelemetrySink&gt; TelemetrySinks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.ApplicationInsights.Extensibility.TelemetrySink&gt; TelemetrySinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetrySinks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TelemetrySinks As IList(Of TelemetrySink)" />
      <MemberSignature Language="F#" Value="member this.TelemetrySinks : System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.TelemetrySink&gt;" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetrySinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.TelemetrySink&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>