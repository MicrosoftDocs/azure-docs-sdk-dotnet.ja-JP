<Type Name="OperationCorrelationTelemetryInitializer" FullName="Microsoft.ApplicationInsights.Extensibility.OperationCorrelationTelemetryInitializer">
  <TypeSignature Language="C#" Value="public class OperationCorrelationTelemetryInitializer : Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationCorrelationTelemetryInitializer extends System.Object implements class Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.OperationCorrelationTelemetryInitializer" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationCorrelationTelemetryInitializer&#xA;Implements ITelemetryInitializer" />
  <TypeSignature Language="F#" Value="type OperationCorrelationTelemetryInitializer = class&#xA;    interface ITelemetryInitializer" />
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
      <InterfaceName>Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="15ddc-101">製品利用統計情報の初期化子 OperationContext AsyncLocal 変数に格納されているコンテキストに基づいて、製品利用統計情報項目のメンバーを追加します。</span><span class="sxs-lookup"><span data-stu-id="15ddc-101">Telemetry initializer that populates OperationContext for the telemetry item based on context stored in AsyncLocal variable.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationCorrelationTelemetryInitializer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.OperationCorrelationTelemetryInitializer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
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
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (Microsoft.ApplicationInsights.Channel.ITelemetry telemetryItem);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class Microsoft.ApplicationInsights.Channel.ITelemetry telemetryItem) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.OperationCorrelationTelemetryInitializer.Initialize(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (telemetryItem As ITelemetry)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit&#xA;override this.Initialize : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="operationCorrelationTelemetryInitializer.Initialize telemetryItem" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer.Initialize(Microsoft.ApplicationInsights.Channel.ITelemetry)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetryItem" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetryItem"><span data-ttu-id="15ddc-102">操作 id を追加する対象の製品利用統計情報項目。</span><span class="sxs-lookup"><span data-stu-id="15ddc-102">Target telemetry item to add operation id.</span></span></param>
        <summary>
            <span data-ttu-id="15ddc-103">既存のテレメトリ項目を初期化します/追加操作 id です。</span><span class="sxs-lookup"><span data-stu-id="15ddc-103">Initializes/Adds operation id to the existing telemetry item.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>