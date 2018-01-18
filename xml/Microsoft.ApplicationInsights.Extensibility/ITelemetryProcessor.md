<Type Name="ITelemetryProcessor" FullName="Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor">
  <TypeSignature Language="C#" Value="public interface ITelemetryProcessor" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITelemetryProcessor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITelemetryProcessor" />
  <TypeSignature Language="F#" Value="type ITelemetryProcessor = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1f8da-101">Application Insights に送信することの一部として利用統計情報の処理に使用されるオブジェクトを表します。</span><span class="sxs-lookup"><span data-stu-id="1f8da-101">Represents an object used to process telemetry as part of sending it to Application Insights.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Process">
      <MemberSignature Language="C#" Value="public void Process (Microsoft.ApplicationInsights.Channel.ITelemetry item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Process(class Microsoft.ApplicationInsights.Channel.ITelemetry item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor.Process(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Process (item As ITelemetry)" />
      <MemberSignature Language="F#" Value="abstract member Process : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="iTelemetryProcessor.Process item" />
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
        <Parameter Name="item" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="1f8da-102">収集された製品利用統計情報項目。</span><span class="sxs-lookup"><span data-stu-id="1f8da-102">A collected Telemetry item.</span></span></param>
        <summary>
            <span data-ttu-id="1f8da-103">収集された製品利用統計情報項目を処理します。</span><span class="sxs-lookup"><span data-stu-id="1f8da-103">Process a collected telemetry item.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>