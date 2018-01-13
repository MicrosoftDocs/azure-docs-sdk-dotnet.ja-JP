<Type Name="DataSourceFilter" FullName="Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter">
  <TypeSignature Language="C#" Value="public class DataSourceFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataSourceFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSourceFilter" />
  <TypeSignature Language="F#" Value="type DataSourceFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            データ ソースのフィルターです。 現在、種類でフィルターのみがサポートされています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSourceFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DataSourceFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSourceFilter (string kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional kind As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter : string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="kind">使用可能な値が含まれます: 'AzureActivityLog'、'ChangeTrackingPath'、'ChangeTrackingDefaultPath'、'ChangeTrackingDefaultRegistry'、'ChangeTrackingCustomRegistry'、'CustomLog'、'CustomLogCollection'、'GenericDataSource'、'IISLogs'、'LinuxPerformanceObject'、'LinuxPerformanceCollection'、'LinuxSyslog'、'LinuxSyslogCollection'、'WindowsEvent'、'WindowsPerformanceCounter'</param>
        <summary>
            DataSourceFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.DataSourceFilter.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定可能な値が含まれます: 'AzureActivityLog'、'ChangeTrackingPath'、'ChangeTrackingDefaultPath'、'ChangeTrackingDefaultRegistry'、'ChangeTrackingCustomRegistry'、'CustomLog'、'CustomLogCollection'、'GenericDataSource'、'IISLogs'、'LinuxPerformanceObject'、'LinuxPerformanceCollection'、'LinuxSyslog'、'LinuxSyslogCollection'、'WindowsEvent'、'WindowsPerformanceCounter'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>