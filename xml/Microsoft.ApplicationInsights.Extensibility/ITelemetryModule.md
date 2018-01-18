<Type Name="ITelemetryModule" FullName="Microsoft.ApplicationInsights.Extensibility.ITelemetryModule">
  <TypeSignature Language="C#" Value="public interface ITelemetryModule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITelemetryModule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryModule" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITelemetryModule" />
  <TypeSignature Language="F#" Value="type ITelemetryModule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d2997-101">初期化をサポートするオブジェクトを表す<see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />です。</span><span class="sxs-lookup"><span data-stu-id="d2997-101">Represents an object that supports initialization from <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.ITelemetryModule.Initialize(Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (configuration As TelemetryConfiguration)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration -&gt; unit" Usage="iTelemetryModule.Initialize configuration" />
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
        <Parameter Name="configuration" Type="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />
      </Parameters>
      <Docs>
        <param name="configuration">To be added.</param>
        <summary>
            <span data-ttu-id="d2997-102">初期化メソッドはすべての構成プロパティが、構成から読み込まれた後に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="d2997-102">Initialize method is called after all configuration properties have been loaded from the configuration.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>