<Type Name="FileSystemApplicationLogsConfig" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig">
  <TypeSignature Language="C#" Value="public class FileSystemApplicationLogsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileSystemApplicationLogsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class FileSystemApplicationLogsConfig" />
  <TypeSignature Language="F#" Value="type FileSystemApplicationLogsConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e1bf6-101">ファイル システムの構成にアプリケーションを記録します。</span><span class="sxs-lookup"><span data-stu-id="e1bf6-101">Application logs to file system configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemApplicationLogsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e1bf6-102">FileSystemApplicationLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1bf6-102">Initializes a new instance of the FileSystemApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileSystemApplicationLogsConfig (Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; level = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; level) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig.#ctor(System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional level As Nullable(Of LogLevel) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig level" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt;" />
      </Parameters>
      <Docs>
        <param name="level"><span data-ttu-id="e1bf6-103">ログ レベル。</span><span class="sxs-lookup"><span data-stu-id="e1bf6-103">Log level.</span></span> <span data-ttu-id="e1bf6-104">使用可能な値が含まれます: 'Off'、'詳細'、'情報'、'警告'、'Error'</span><span class="sxs-lookup"><span data-stu-id="e1bf6-104">Possible values include: 'Off', 'Verbose', 'Information', 'Warning', 'Error'</span></span></param>
        <summary>
            <span data-ttu-id="e1bf6-105">FileSystemApplicationLogsConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1bf6-105">Initializes a new instance of the FileSystemApplicationLogsConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of LogLevel)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.FileSystemApplicationLogsConfig.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.LogLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1bf6-106">取得またはログ レベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1bf6-106">Gets or sets log level.</span></span> <span data-ttu-id="e1bf6-107">使用可能な値が含まれます: 'Off'、'詳細'、'情報'、'警告'、'Error'</span><span class="sxs-lookup"><span data-stu-id="e1bf6-107">Possible values include: 'Off', 'Verbose', 'Information', 'Warning', 'Error'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>