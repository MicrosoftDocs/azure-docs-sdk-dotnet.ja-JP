<Type Name="BootDiagnosticsInstanceView" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView">
  <TypeSignature Language="C#" Value="public class BootDiagnosticsInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BootDiagnosticsInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class BootDiagnosticsInstanceView" />
  <TypeSignature Language="F#" Value="type BootDiagnosticsInstanceView = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8069d-101">仮想マシンのブート診断のインスタンス ビューです。</span><span class="sxs-lookup"><span data-stu-id="8069d-101">The instance view of a virtual machine boot diagnostics.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BootDiagnosticsInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8069d-102">BootDiagnosticsInstanceView クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8069d-102">Initializes a new instance of the BootDiagnosticsInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BootDiagnosticsInstanceView (string consoleScreenshotBlobUri = null, string serialConsoleLogBlobUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string consoleScreenshotBlobUri, string serialConsoleLogBlobUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional consoleScreenshotBlobUri As String = null, Optional serialConsoleLogBlobUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView : string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView (consoleScreenshotBlobUri, serialConsoleLogBlobUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="consoleScreenshotBlobUri" Type="System.String" />
        <Parameter Name="serialConsoleLogBlobUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="consoleScreenshotBlobUri"><span data-ttu-id="8069d-103">コンソールのスクリーン ショット blob の URI。</span><span class="sxs-lookup"><span data-stu-id="8069d-103">The console screenshot blob URI.</span></span></param>
        <param name="serialConsoleLogBlobUri"><span data-ttu-id="8069d-104">Linux のシリアル コンソール ログ blob の Uri。</span><span class="sxs-lookup"><span data-stu-id="8069d-104">The Linux serial console log blob Uri.</span></span></param>
        <summary>
            <span data-ttu-id="8069d-105">BootDiagnosticsInstanceView クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8069d-105">Initializes a new instance of the BootDiagnosticsInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsoleScreenshotBlobUri">
      <MemberSignature Language="C#" Value="public string ConsoleScreenshotBlobUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsoleScreenshotBlobUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView.ConsoleScreenshotBlobUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsoleScreenshotBlobUri As String" />
      <MemberSignature Language="F#" Value="member this.ConsoleScreenshotBlobUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView.ConsoleScreenshotBlobUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="consoleScreenshotBlobUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8069d-106">取得またはコンソールのスクリーン ショット blob URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="8069d-106">Gets or sets the console screenshot blob URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialConsoleLogBlobUri">
      <MemberSignature Language="C#" Value="public string SerialConsoleLogBlobUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SerialConsoleLogBlobUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView.SerialConsoleLogBlobUri" />
      <MemberSignature Language="VB.NET" Value="Public Property SerialConsoleLogBlobUri As String" />
      <MemberSignature Language="F#" Value="member this.SerialConsoleLogBlobUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnosticsInstanceView.SerialConsoleLogBlobUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serialConsoleLogBlobUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8069d-107">取得または Linux のシリアル コンソールのログ blob の Uri を設定します。</span><span class="sxs-lookup"><span data-stu-id="8069d-107">Gets or sets the Linux serial console log blob Uri.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>