<Type Name="TelemetryProcessorChainBuilder" FullName="Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder">
  <TypeSignature Language="C#" Value="public sealed class TelemetryProcessorChainBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TelemetryProcessorChainBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TelemetryProcessorChainBuilder" />
  <TypeSignature Language="F#" Value="type TelemetryProcessorChainBuilder = class" />
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
            <span data-ttu-id="d2060-101">TelemetryProcessorChain の構築に使用するオブジェクトを表します。</span><span class="sxs-lookup"><span data-stu-id="d2060-101">Represents an object used to Build a TelemetryProcessorChain.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryProcessorChainBuilder (Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder.#ctor(Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configuration As TelemetryConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder : Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration -&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder" Usage="new Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder configuration" />
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
        <param name="configuration"> <span data-ttu-id="d2060-102"><see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />インスタンスを構築処理チェーンに設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d2060-102">The <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> instance to which the constructed processing chain should be set to.</span></span> </param>
        <summary>
            <span data-ttu-id="d2060-103"><see cref="T:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d2060-103">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryProcessorChainBuilder (Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration, Microsoft.ApplicationInsights.Extensibility.TelemetrySink telemetrySink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration, class Microsoft.ApplicationInsights.Extensibility.TelemetrySink telemetrySink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder.#ctor(Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration,Microsoft.ApplicationInsights.Extensibility.TelemetrySink)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder : Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration * Microsoft.ApplicationInsights.Extensibility.TelemetrySink -&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder" Usage="new Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder (configuration, telemetrySink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configuration" Type="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />
        <Parameter Name="telemetrySink" Type="Microsoft.ApplicationInsights.Extensibility.TelemetrySink" />
      </Parameters>
      <Docs>
        <param name="configuration">To be added.</param>
        <param name="telemetrySink">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Build">
      <MemberSignature Language="C#" Value="public void Build ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Build() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder.Build" />
      <MemberSignature Language="VB.NET" Value="Public Sub Build ()" />
      <MemberSignature Language="F#" Value="member this.Build : unit -&gt; unit" Usage="telemetryProcessorChainBuilder.Build " />
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
            <span data-ttu-id="d2060-104">ビルドのチェーンにリンクされている<see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor" />をインスタンス化し、渡された構成オブジェクトの同じを設定します。</span><span class="sxs-lookup"><span data-stu-id="d2060-104">Builds the chain of linked <see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor" /> instances and sets the same in configuration object passed.</span></span>
            <span data-ttu-id="d2060-105">転送を処理するための特別な遠隔測定プロセッサは常に、チェーン内の最後のプロセッサとして追加されます。</span><span class="sxs-lookup"><span data-stu-id="d2060-105">A special telemetry processor for handling Transmission is always appended as the last processor in the chain.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Use">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder Use (Func&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor,Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt; telemetryProcessorFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder Use(class System.Func`2&lt;class Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor, class Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt; telemetryProcessorFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder.Use(System.Func{Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor,Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor})" />
      <MemberSignature Language="VB.NET" Value="Public Function Use (telemetryProcessorFactory As Func(Of ITelemetryProcessor, ITelemetryProcessor)) As TelemetryProcessorChainBuilder" />
      <MemberSignature Language="F#" Value="member this.Use : Func&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor, Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt; -&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder" Usage="telemetryProcessorChainBuilder.Use telemetryProcessorFactory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetryProcessorFactory" Type="System.Func&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor,Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt;" />
      </Parameters>
      <Docs>
        <param name="telemetryProcessorFactory"><span data-ttu-id="d2060-106">返すデリゲート、 <see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor" /> 、次を指定された<see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor" />呼び出しチェーンにします。</span><span class="sxs-lookup"><span data-stu-id="d2060-106">A delegate that returns a <see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor" /> , given the next <see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor" /> in the call chain.</span></span></param>
        <summary>
            <span data-ttu-id="d2060-107">プロセッサのチェーンに TelemetryProcessor を追加するには、工場出荷時の指定を使用します。</span><span class="sxs-lookup"><span data-stu-id="d2060-107">Uses given factory to add TelemetryProcessor to the chain of processors.</span></span> <span data-ttu-id="d2060-108">チェーン内のプロセッサがそれらを追加する同じ順序で呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="d2060-108">The processors in the chain will be invoked in the same order in which they are added.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>