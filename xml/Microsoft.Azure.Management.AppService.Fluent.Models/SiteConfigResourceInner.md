<Type Name="SiteConfigResourceInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner">
  <TypeSignature Language="C#" Value="public class SiteConfigResourceInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteConfigResourceInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteConfigResourceInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteConfigResourceInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f8c6a-101">ARM リソース web アプリの構成。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-101">Web app configuration ARM resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteConfigResourceInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-102">SiteConfigResourceInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-102">Initializes a new instance of the SiteConfigResourceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteConfigResourceInner (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;int&gt; numberOfWorkers = null, System.Collections.Generic.IList&lt;string&gt; defaultDocuments = null, string netFrameworkVersion = null, string phpVersion = null, string pythonVersion = null, string nodeVersion = null, string linuxFxVersion = null, Nullable&lt;bool&gt; requestTracingEnabled = null, Nullable&lt;DateTime&gt; requestTracingExpirationTime = null, Nullable&lt;bool&gt; remoteDebuggingEnabled = null, string remoteDebuggingVersion = null, Nullable&lt;bool&gt; httpLoggingEnabled = null, Nullable&lt;int&gt; logsDirectorySizeLimit = null, Nullable&lt;bool&gt; detailedErrorLoggingEnabled = null, string publishingUsername = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; appSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringInfo&gt; connectionStrings = null, Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey machineKey = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping&gt; handlerMappings = null, string documentRoot = null, string scmType = null, Nullable&lt;bool&gt; use32BitWorkerProcess = null, Nullable&lt;bool&gt; webSocketsEnabled = null, Nullable&lt;bool&gt; alwaysOn = null, string javaVersion = null, string javaContainer = null, string javaContainerVersion = null, string appCommandLine = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode&gt; managedPipelineMode = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualApplication&gt; virtualApplications = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteLoadBalancing&gt; loadBalancing = null, Microsoft.Azure.Management.AppService.Fluent.Models.Experiments experiments = null, Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits limits = null, Nullable&lt;bool&gt; autoHealEnabled = null, Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules autoHealRules = null, string tracingOptions = null, string vnetName = null, Microsoft.Azure.Management.AppService.Fluent.Models.CorsSettings cors = null, Microsoft.Azure.Management.AppService.Fluent.Models.PushSettingsInner push = null, Microsoft.Azure.Management.AppService.Fluent.Models.ApiDefinitionInfo apiDefinition = null, string autoSwapSlotName = null, Nullable&lt;bool&gt; localMySqlEnabled = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.IpSecurityRestriction&gt; ipSecurityRestrictions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;int32&gt; numberOfWorkers, class System.Collections.Generic.IList`1&lt;string&gt; defaultDocuments, string netFrameworkVersion, string phpVersion, string pythonVersion, string nodeVersion, string linuxFxVersion, valuetype System.Nullable`1&lt;bool&gt; requestTracingEnabled, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; requestTracingExpirationTime, valuetype System.Nullable`1&lt;bool&gt; remoteDebuggingEnabled, string remoteDebuggingVersion, valuetype System.Nullable`1&lt;bool&gt; httpLoggingEnabled, valuetype System.Nullable`1&lt;int32&gt; logsDirectorySizeLimit, valuetype System.Nullable`1&lt;bool&gt; detailedErrorLoggingEnabled, string publishingUsername, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; appSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringInfo&gt; connectionStrings, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey machineKey, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping&gt; handlerMappings, string documentRoot, string scmType, valuetype System.Nullable`1&lt;bool&gt; use32BitWorkerProcess, valuetype System.Nullable`1&lt;bool&gt; webSocketsEnabled, valuetype System.Nullable`1&lt;bool&gt; alwaysOn, string javaVersion, string javaContainer, string javaContainerVersion, string appCommandLine, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode&gt; managedPipelineMode, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VirtualApplication&gt; virtualApplications, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SiteLoadBalancing&gt; loadBalancing, class Microsoft.Azure.Management.AppService.Fluent.Models.Experiments experiments, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits limits, valuetype System.Nullable`1&lt;bool&gt; autoHealEnabled, class Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules autoHealRules, string tracingOptions, string vnetName, class Microsoft.Azure.Management.AppService.Fluent.Models.CorsSettings cors, class Microsoft.Azure.Management.AppService.Fluent.Models.PushSettingsInner push, class Microsoft.Azure.Management.AppService.Fluent.Models.ApiDefinitionInfo apiDefinition, string autoSwapSlotName, valuetype System.Nullable`1&lt;bool&gt; localMySqlEnabled, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.IpSecurityRestriction&gt; ipSecurityRestrictions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringInfo},Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey,System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.VirtualApplication},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.SiteLoadBalancing},Microsoft.Azure.Management.AppService.Fluent.Models.Experiments,Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits,System.Nullable{System.Boolean},Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.CorsSettings,Microsoft.Azure.Management.AppService.Fluent.Models.PushSettingsInner,Microsoft.Azure.Management.AppService.Fluent.Models.ApiDefinitionInfo,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.IpSecurityRestriction})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner : string * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringInfo&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualApplication&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteLoadBalancing&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.Experiments * Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits * Nullable&lt;bool&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.CorsSettings * Microsoft.Azure.Management.AppService.Fluent.Models.PushSettingsInner * Microsoft.Azure.Management.AppService.Fluent.Models.ApiDefinitionInfo * string * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.IpSecurityRestriction&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner (id, name, kind, type, numberOfWorkers, defaultDocuments, netFrameworkVersion, phpVersion, pythonVersion, nodeVersion, linuxFxVersion, requestTracingEnabled, requestTracingExpirationTime, remoteDebuggingEnabled, remoteDebuggingVersion, httpLoggingEnabled, logsDirectorySizeLimit, detailedErrorLoggingEnabled, publishingUsername, appSettings, connectionStrings, machineKey, handlerMappings, documentRoot, scmType, use32BitWorkerProcess, webSocketsEnabled, alwaysOn, javaVersion, javaContainer, javaContainerVersion, appCommandLine, managedPipelineMode, virtualApplications, loadBalancing, experiments, limits, autoHealEnabled, autoHealRules, tracingOptions, vnetName, cors, push, apiDefinition, autoSwapSlotName, localMySqlEnabled, ipSecurityRestrictions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="numberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="defaultDocuments" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="netFrameworkVersion" Type="System.String" />
        <Parameter Name="phpVersion" Type="System.String" />
        <Parameter Name="pythonVersion" Type="System.String" />
        <Parameter Name="nodeVersion" Type="System.String" />
        <Parameter Name="linuxFxVersion" Type="System.String" />
        <Parameter Name="requestTracingEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="requestTracingExpirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="remoteDebuggingEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="remoteDebuggingVersion" Type="System.String" />
        <Parameter Name="httpLoggingEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="logsDirectorySizeLimit" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="detailedErrorLoggingEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="publishingUsername" Type="System.String" />
        <Parameter Name="appSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt;" />
        <Parameter Name="connectionStrings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringInfo&gt;" />
        <Parameter Name="machineKey" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey" />
        <Parameter Name="handlerMappings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping&gt;" />
        <Parameter Name="documentRoot" Type="System.String" />
        <Parameter Name="scmType" Type="System.String" />
        <Parameter Name="use32BitWorkerProcess" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="webSocketsEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="alwaysOn" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="javaVersion" Type="System.String" />
        <Parameter Name="javaContainer" Type="System.String" />
        <Parameter Name="javaContainerVersion" Type="System.String" />
        <Parameter Name="appCommandLine" Type="System.String" />
        <Parameter Name="managedPipelineMode" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode&gt;" />
        <Parameter Name="virtualApplications" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualApplication&gt;" />
        <Parameter Name="loadBalancing" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteLoadBalancing&gt;" />
        <Parameter Name="experiments" Type="Microsoft.Azure.Management.AppService.Fluent.Models.Experiments" />
        <Parameter Name="limits" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits" />
        <Parameter Name="autoHealEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="autoHealRules" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules" />
        <Parameter Name="tracingOptions" Type="System.String" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="cors" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CorsSettings" />
        <Parameter Name="push" Type="Microsoft.Azure.Management.AppService.Fluent.Models.PushSettingsInner" />
        <Parameter Name="apiDefinition" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ApiDefinitionInfo" />
        <Parameter Name="autoSwapSlotName" Type="System.String" />
        <Parameter Name="localMySqlEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ipSecurityRestrictions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.IpSecurityRestriction&gt;" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="numberOfWorkers">To be added.</param>
        <param name="defaultDocuments">To be added.</param>
        <param name="netFrameworkVersion">To be added.</param>
        <param name="phpVersion">To be added.</param>
        <param name="pythonVersion">To be added.</param>
        <param name="nodeVersion">To be added.</param>
        <param name="linuxFxVersion">To be added.</param>
        <param name="requestTracingEnabled">To be added.</param>
        <param name="requestTracingExpirationTime">To be added.</param>
        <param name="remoteDebuggingEnabled">To be added.</param>
        <param name="remoteDebuggingVersion">To be added.</param>
        <param name="httpLoggingEnabled">To be added.</param>
        <param name="logsDirectorySizeLimit">To be added.</param>
        <param name="detailedErrorLoggingEnabled">To be added.</param>
        <param name="publishingUsername">To be added.</param>
        <param name="appSettings">To be added.</param>
        <param name="connectionStrings">To be added.</param>
        <param name="machineKey">To be added.</param>
        <param name="handlerMappings">To be added.</param>
        <param name="documentRoot">To be added.</param>
        <param name="scmType">To be added.</param>
        <param name="use32BitWorkerProcess">To be added.</param>
        <param name="webSocketsEnabled">To be added.</param>
        <param name="alwaysOn">To be added.</param>
        <param name="javaVersion">To be added.</param>
        <param name="javaContainer">To be added.</param>
        <param name="javaContainerVersion">To be added.</param>
        <param name="appCommandLine">To be added.</param>
        <param name="managedPipelineMode">To be added.</param>
        <param name="virtualApplications">To be added.</param>
        <param name="loadBalancing">To be added.</param>
        <param name="experiments">To be added.</param>
        <param name="limits">To be added.</param>
        <param name="autoHealEnabled">To be added.</param>
        <param name="autoHealRules">To be added.</param>
        <param name="tracingOptions">To be added.</param>
        <param name="vnetName">To be added.</param>
        <param name="cors">To be added.</param>
        <param name="push">To be added.</param>
        <param name="apiDefinition">To be added.</param>
        <param name="autoSwapSlotName">To be added.</param>
        <param name="localMySqlEnabled">To be added.</param>
        <param name="ipSecurityRestrictions">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlwaysOn">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AlwaysOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AlwaysOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AlwaysOn" />
      <MemberSignature Language="VB.NET" Value="Public Property AlwaysOn As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AlwaysOn : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AlwaysOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.alwaysOn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-103">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; Always On が有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-103">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if Always On is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiDefinition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.ApiDefinitionInfo ApiDefinition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.ApiDefinitionInfo ApiDefinition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.ApiDefinition" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiDefinition As ApiDefinitionInfo" />
      <MemberSignature Language="F#" Value="member this.ApiDefinition : Microsoft.Azure.Management.AppService.Fluent.Models.ApiDefinitionInfo with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.ApiDefinition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.apiDefinition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.ApiDefinitionInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-104">取得またはアプリの正式な API 定義に関する情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-104">Gets or sets information about the formal API definition for the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppCommandLine">
      <MemberSignature Language="C#" Value="public string AppCommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppCommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AppCommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property AppCommandLine As String" />
      <MemberSignature Language="F#" Value="member this.AppCommandLine : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AppCommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appCommandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-105">取得またはアプリを起動するコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-105">Gets or sets app command line to launch.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; AppSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; AppSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AppSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AppSettings As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.AppSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AppSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-106">取得またはアプリケーションの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-106">Gets or sets application settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoHealEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoHealEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoHealEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AutoHealEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoHealEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoHealEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AutoHealEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoHealEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-107">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 場合は自動修復が有効である、それ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-107">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if Auto Heal is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoHealRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules AutoHealRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules AutoHealRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AutoHealRules" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoHealRules As AutoHealRules" />
      <MemberSignature Language="F#" Value="member this.AutoHealRules : Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AutoHealRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoHealRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.AutoHealRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-108">取得または自動 Heal ルールを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-108">Gets or sets auto Heal rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoSwapSlotName">
      <MemberSignature Language="C#" Value="public string AutoSwapSlotName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoSwapSlotName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AutoSwapSlotName" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoSwapSlotName As String" />
      <MemberSignature Language="F#" Value="member this.AutoSwapSlotName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.AutoSwapSlotName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoSwapSlotName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-109">取得または自動スワップ スロット名を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-109">Gets or sets auto-swap slot name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStrings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringInfo&gt; ConnectionStrings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringInfo&gt; ConnectionStrings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.ConnectionStrings" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionStrings As IList(Of ConnStringInfo)" />
      <MemberSignature Language="F#" Value="member this.ConnectionStrings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringInfo&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.ConnectionStrings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionStrings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ConnStringInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-110">取得または接続文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-110">Gets or sets connection strings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cors">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CorsSettings Cors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CorsSettings Cors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Cors" />
      <MemberSignature Language="VB.NET" Value="Public Property Cors As CorsSettings" />
      <MemberSignature Language="F#" Value="member this.Cors : Microsoft.Azure.Management.AppService.Fluent.Models.CorsSettings with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Cors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CorsSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-111">取得またはクロス オリジン リソース共有 (CORS) の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-111">Gets or sets cross-Origin Resource Sharing (CORS) settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultDocuments">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DefaultDocuments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DefaultDocuments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.DefaultDocuments" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultDocuments As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DefaultDocuments : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.DefaultDocuments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultDocuments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-112">取得または既定のドキュメントを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-112">Gets or sets default documents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailedErrorLoggingEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DetailedErrorLoggingEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DetailedErrorLoggingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.DetailedErrorLoggingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailedErrorLoggingEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DetailedErrorLoggingEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.DetailedErrorLoggingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.detailedErrorLoggingEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-113">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 詳細なエラーのログ記録が有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-113">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if detailed error logging is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentRoot">
      <MemberSignature Language="C#" Value="public string DocumentRoot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DocumentRoot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.DocumentRoot" />
      <MemberSignature Language="VB.NET" Value="Public Property DocumentRoot As String" />
      <MemberSignature Language="F#" Value="member this.DocumentRoot : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.DocumentRoot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.documentRoot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-114">取得またはドキュメントのルートを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-114">Gets or sets document root.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Experiments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Experiments Experiments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Experiments Experiments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Experiments" />
      <MemberSignature Language="VB.NET" Value="Public Property Experiments As Experiments" />
      <MemberSignature Language="F#" Value="member this.Experiments : Microsoft.Azure.Management.AppService.Fluent.Models.Experiments with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Experiments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.experiments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Experiments</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-115">取得または設定 polymophic 型の回避です。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-115">Gets or sets this is work around for polymophic types.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandlerMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping&gt; HandlerMappings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping&gt; HandlerMappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.HandlerMappings" />
      <MemberSignature Language="VB.NET" Value="Public Property HandlerMappings As IList(Of HandlerMapping)" />
      <MemberSignature Language="F#" Value="member this.HandlerMappings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.HandlerMappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.handlerMappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-116">取得またはハンドラー マッピングを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-116">Gets or sets handler mappings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpLoggingEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HttpLoggingEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HttpLoggingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.HttpLoggingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpLoggingEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HttpLoggingEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.HttpLoggingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.httpLoggingEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-117">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; HTTP ログ記録が有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-117">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if HTTP logging is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpSecurityRestrictions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.IpSecurityRestriction&gt; IpSecurityRestrictions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.IpSecurityRestriction&gt; IpSecurityRestrictions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.IpSecurityRestrictions" />
      <MemberSignature Language="VB.NET" Value="Public Property IpSecurityRestrictions As IList(Of IpSecurityRestriction)" />
      <MemberSignature Language="F#" Value="member this.IpSecurityRestrictions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.IpSecurityRestriction&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.IpSecurityRestrictions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipSecurityRestrictions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.IpSecurityRestriction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-118">取得または IP セキュリティ制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-118">Gets or sets IP security restrictions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaContainer">
      <MemberSignature Language="C#" Value="public string JavaContainer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.JavaContainer" />
      <MemberSignature Language="VB.NET" Value="Public Property JavaContainer As String" />
      <MemberSignature Language="F#" Value="member this.JavaContainer : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.JavaContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.javaContainer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-119">取得または java コンテナーを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-119">Gets or sets java container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaContainerVersion">
      <MemberSignature Language="C#" Value="public string JavaContainerVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaContainerVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.JavaContainerVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property JavaContainerVersion As String" />
      <MemberSignature Language="F#" Value="member this.JavaContainerVersion : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.JavaContainerVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.javaContainerVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-120">取得またはコンテナーの java バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-120">Gets or sets java container version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaVersion">
      <MemberSignature Language="C#" Value="public string JavaVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.JavaVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property JavaVersion As String" />
      <MemberSignature Language="F#" Value="member this.JavaVersion : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.JavaVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.javaVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-121">取得または java バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-121">Gets or sets java version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limits">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits Limits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits Limits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Limits" />
      <MemberSignature Language="VB.NET" Value="Public Property Limits As SiteLimits" />
      <MemberSignature Language="F#" Value="member this.Limits : Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Limits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.limits")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-122">取得またはサイトの制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-122">Gets or sets site limits.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxFxVersion">
      <MemberSignature Language="C#" Value="public string LinuxFxVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinuxFxVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.LinuxFxVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxFxVersion As String" />
      <MemberSignature Language="F#" Value="member this.LinuxFxVersion : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.LinuxFxVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linuxFxVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-123">取得または設定の linux アプリケーション フレームワークとバージョン</span><span class="sxs-lookup"><span data-stu-id="f8c6a-123">Gets or sets linux App Framework and version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancing">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteLoadBalancing&gt; LoadBalancing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SiteLoadBalancing&gt; LoadBalancing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.LoadBalancing" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancing As Nullable(Of SiteLoadBalancing)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancing : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteLoadBalancing&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.LoadBalancing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteLoadBalancing&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-124">取得またはサイトの負荷分散を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-124">Gets or sets site load balancing.</span></span> <span data-ttu-id="f8c6a-125">使用可能な値が含まれます: 'WeightedRoundRobin'、'LeastRequests'、'LeastResponseTime'、'WeightedTotalTraffic'、'RequestHash'</span><span class="sxs-lookup"><span data-stu-id="f8c6a-125">Possible values include: 'WeightedRoundRobin', 'LeastRequests', 'LeastResponseTime', 'WeightedTotalTraffic', 'RequestHash'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalMySqlEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; LocalMySqlEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; LocalMySqlEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.LocalMySqlEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalMySqlEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.LocalMySqlEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.LocalMySqlEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.localMySqlEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-126">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; ローカル MySQL; を有効にするそれ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-126">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to enable local MySQL; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogsDirectorySizeLimit">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LogsDirectorySizeLimit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LogsDirectorySizeLimit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.LogsDirectorySizeLimit" />
      <MemberSignature Language="VB.NET" Value="Public Property LogsDirectorySizeLimit As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LogsDirectorySizeLimit : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.LogsDirectorySizeLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.logsDirectorySizeLimit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-127">取得または HTTP ログ ディレクトリのサイズ制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-127">Gets or sets HTTP logs directory size limit.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MachineKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey MachineKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey MachineKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.MachineKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MachineKey As SiteMachineKey" />
      <MemberSignature Language="F#" Value="member this.MachineKey : Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.MachineKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.machineKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SiteMachineKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-128">サイトの MachineKey を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-128">Gets site MachineKey.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedPipelineMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode&gt; ManagedPipelineMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode&gt; ManagedPipelineMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.ManagedPipelineMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedPipelineMode As Nullable(Of ManagedPipelineMode)" />
      <MemberSignature Language="F#" Value="member this.ManagedPipelineMode : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.ManagedPipelineMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.managedPipelineMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-129">取得またはマネージ パイプライン モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-129">Gets or sets managed pipeline mode.</span></span> <span data-ttu-id="f8c6a-130">使用可能な値が含まれます: '統合'、'Classic'</span><span class="sxs-lookup"><span data-stu-id="f8c6a-130">Possible values include: 'Integrated', 'Classic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetFrameworkVersion">
      <MemberSignature Language="C#" Value="public string NetFrameworkVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NetFrameworkVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.NetFrameworkVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property NetFrameworkVersion As String" />
      <MemberSignature Language="F#" Value="member this.NetFrameworkVersion : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.NetFrameworkVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.netFrameworkVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-131">取得または .NET Framework のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-131">Gets or sets .NET Framework version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeVersion">
      <MemberSignature Language="C#" Value="public string NodeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.NodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.NodeVersion : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.NodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-132">取得または Node.js のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-132">Gets or sets version of Node.js.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfWorkers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.NumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfWorkers : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.NumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-133">取得またはワーカーの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-133">Gets or sets number of workers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PhpVersion">
      <MemberSignature Language="C#" Value="public string PhpVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PhpVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.PhpVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PhpVersion As String" />
      <MemberSignature Language="F#" Value="member this.PhpVersion : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.PhpVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.phpVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-134">取得または PHP のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-134">Gets or sets version of PHP.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishingUsername">
      <MemberSignature Language="C#" Value="public string PublishingUsername { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishingUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.PublishingUsername" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishingUsername As String" />
      <MemberSignature Language="F#" Value="member this.PublishingUsername : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.PublishingUsername" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publishingUsername")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-135">取得または発行ユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-135">Gets or sets publishing user name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Push">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.PushSettingsInner Push { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.PushSettingsInner Push" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Push" />
      <MemberSignature Language="VB.NET" Value="Public Property Push As PushSettingsInner" />
      <MemberSignature Language="F#" Value="member this.Push : Microsoft.Azure.Management.AppService.Fluent.Models.PushSettingsInner with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Push" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.push")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.PushSettingsInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-136">取得またはプッシュ エンドポイントの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-136">Gets or sets push endpoint settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonVersion">
      <MemberSignature Language="C#" Value="public string PythonVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.PythonVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonVersion As String" />
      <MemberSignature Language="F#" Value="member this.PythonVersion : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.PythonVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pythonVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-137">取得または Python のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-137">Gets or sets version of Python.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteDebuggingEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RemoteDebuggingEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RemoteDebuggingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.RemoteDebuggingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteDebuggingEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoteDebuggingEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.RemoteDebuggingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.remoteDebuggingEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-138">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; リモート デバッグが有効である、それ以外の場合、場合&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-138">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if remote debugging is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteDebuggingVersion">
      <MemberSignature Language="C#" Value="public string RemoteDebuggingVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteDebuggingVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.RemoteDebuggingVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteDebuggingVersion As String" />
      <MemberSignature Language="F#" Value="member this.RemoteDebuggingVersion : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.RemoteDebuggingVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.remoteDebuggingVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-139">取得またはリモートのデバッグ バージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-139">Gets or sets remote debugging version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTracingEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequestTracingEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequestTracingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.RequestTracingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestTracingEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequestTracingEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.RequestTracingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestTracingEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-140">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 要求のトレースが有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-140">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if request tracing is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTracingExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RequestTracingExpirationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RequestTracingExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.RequestTracingExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestTracingExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RequestTracingExpirationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.RequestTracingExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestTracingExpirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-141">取得または要求のトレースの有効期限を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-141">Gets or sets request tracing expiration time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScmType">
      <MemberSignature Language="C#" Value="public string ScmType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScmType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.ScmType" />
      <MemberSignature Language="VB.NET" Value="Public Property ScmType As String" />
      <MemberSignature Language="F#" Value="member this.ScmType : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.ScmType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scmType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-142">取得または SCM 型を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-142">Gets or sets SCM type.</span></span> <span data-ttu-id="f8c6a-143">使用可能な値が含まれます 'None'、'Dropbox'、'Tfs'、'LocalGit'、'GitHub'、'CodePlexGit'、'CodePlexHg'、'BitbucketGit'、'BitbucketHg'、'ExternalGit'、'ExternalHg'、'OneDrive'、'VSO'。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-143">Possible values include: 'None', 'Dropbox', 'Tfs', 'LocalGit', 'GitHub', 'CodePlexGit', 'CodePlexHg', 'BitbucketGit', 'BitbucketHg', 'ExternalGit', 'ExternalHg', 'OneDrive', 'VSO'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TracingOptions">
      <MemberSignature Language="C#" Value="public string TracingOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TracingOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.TracingOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property TracingOptions As String" />
      <MemberSignature Language="F#" Value="member this.TracingOptions : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.TracingOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tracingOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-144">取得またはトレース オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-144">Gets or sets tracing options.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Use32BitWorkerProcess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Use32BitWorkerProcess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Use32BitWorkerProcess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Use32BitWorkerProcess" />
      <MemberSignature Language="VB.NET" Value="Public Property Use32BitWorkerProcess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Use32BitWorkerProcess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Use32BitWorkerProcess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.use32BitWorkerProcess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-145">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 32 ビット ワーカー プロセスを使用してそれ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-145">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to use 32-bit worker process; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="siteConfigResourceInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-146">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-146">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f8c6a-147">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-147">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualApplications">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualApplication&gt; VirtualApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VirtualApplication&gt; VirtualApplications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.VirtualApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualApplications As IList(Of VirtualApplication)" />
      <MemberSignature Language="F#" Value="member this.VirtualApplications : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualApplication&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.VirtualApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualApplications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualApplication&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-148">取得または、仮想アプリケーションを設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-148">Gets or sets virtual applications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetName">
      <MemberSignature Language="C#" Value="public string VnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.VnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.VnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-149">取得または仮想ネットワーク名を設定します。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-149">Gets or sets virtual Network name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebSocketsEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WebSocketsEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WebSocketsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.WebSocketsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property WebSocketsEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WebSocketsEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfigResourceInner.WebSocketsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.webSocketsEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f8c6a-150">取得または設定&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; WebSocket が有効になっている、それ以外の場合は&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="f8c6a-150">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if WebSocket is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>