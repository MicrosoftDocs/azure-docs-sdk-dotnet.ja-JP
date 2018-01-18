<Type Name="ITelemetryInitializer" FullName="Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer">
  <TypeSignature Language="C#" Value="public interface ITelemetryInitializer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITelemetryInitializer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITelemetryInitializer" />
  <TypeSignature Language="F#" Value="type ITelemetryInitializer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7f504-101">初期化するオブジェクトを表す<see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7f504-101">Represents an object that initializes <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> objects.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="7f504-102"><see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" />インスタンスを使用して<see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" />のプロパティを自動的に初期化するために、<see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7f504-102">The <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" /> instances use <see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" /> objects to automatically initialize properties of the <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> objects.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (Microsoft.ApplicationInsights.Channel.ITelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class Microsoft.ApplicationInsights.Channel.ITelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer.Initialize(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (telemetry As ITelemetry)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="iTelemetryInitializer.Initialize telemetry" />
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
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            <span data-ttu-id="7f504-103">指定したプロパティを初期化<see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7f504-103">Initializes properties of the specified <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>