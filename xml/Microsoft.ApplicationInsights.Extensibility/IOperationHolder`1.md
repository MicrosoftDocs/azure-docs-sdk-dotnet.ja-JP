<Type Name="IOperationHolder&lt;T&gt;" FullName="Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IOperationHolder&lt;T&gt; : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperationHolder`1&lt;T&gt; implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperationHolder(Of T)&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IOperationHolder&lt;'T&gt; = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="157b1-101">終了要求で追跡される製品利用統計情報を保持する操作のアイテムを表します。</span><span class="sxs-lookup"><span data-stu-id="157b1-101">Represents the operation item that holds telemetry which is tracked on end request.</span></span> <span data-ttu-id="157b1-102">操作は、WEB または SQL のいずれかの依存関係を関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="157b1-102">Operation can be associated with either WEB or SQL dependencies.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Telemetry">
      <MemberSignature Language="C#" Value="public T Telemetry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Telemetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1.Telemetry" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Telemetry As T" />
      <MemberSignature Language="F#" Value="member this.Telemetry : 'T" Usage="Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T&gt;.Telemetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="157b1-103">ClientExtensions の StartOperation 関数が呼び出されるときに作成される目的のテレメトリ項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="157b1-103">Gets Telemetry item of interest that is created when StartOperation function of ClientExtensions is invoked.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>