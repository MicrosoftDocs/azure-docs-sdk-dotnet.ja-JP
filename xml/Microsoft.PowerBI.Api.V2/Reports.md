<Type Name="Reports" FullName="Microsoft.PowerBI.Api.V2.Reports">
  <TypeSignature Language="C#" Value="public class Reports : Microsoft.PowerBI.Api.V2.IReports, Microsoft.Rest.IServiceOperations&lt;Microsoft.PowerBI.Api.V2.PowerBIClient&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Reports extends System.Object implements class Microsoft.PowerBI.Api.V2.IReports, class Microsoft.Rest.IServiceOperations`1&lt;class Microsoft.PowerBI.Api.V2.PowerBIClient&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.PowerBI.Api.V2.Reports" />
  <TypeSignature Language="VB.NET" Value="Public Class Reports&#xA;Implements IReports, IServiceOperations(Of PowerBIClient)" />
  <TypeSignature Language="F#" Value="type Reports = class&#xA;    interface IServiceOperations&lt;PowerBIClient&gt;&#xA;    interface IReports" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
    <AssemblyVersion>2.0.3.17253</AssemblyVersion>
    <AssemblyVersion>2.0.8.17320</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.PowerBI.Api.V2.IReports</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.IServiceOperations&lt;Microsoft.PowerBI.Api.V2.PowerBIClient&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Reports (Microsoft.PowerBI.Api.V2.PowerBIClient client);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.PowerBI.Api.V2.PowerBIClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.#ctor(Microsoft.PowerBI.Api.V2.PowerBIClient)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (client As PowerBIClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.PowerBI.Api.V2.Reports : Microsoft.PowerBI.Api.V2.PowerBIClient -&gt; Microsoft.PowerBI.Api.V2.Reports" Usage="new Microsoft.PowerBI.Api.V2.Reports client" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.PowerBI.Api.V2.PowerBIClient" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Client">
      <MemberSignature Language="C#" Value="public Microsoft.PowerBI.Api.V2.PowerBIClient Client { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.PowerBI.Api.V2.PowerBIClient Client" />
      <MemberSignature Language="DocId" Value="P:Microsoft.PowerBI.Api.V2.Reports.Client" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Client As PowerBIClient" />
      <MemberSignature Language="F#" Value="member this.Client : Microsoft.PowerBI.Api.V2.PowerBIClient" Usage="Microsoft.PowerBI.Api.V2.Reports.Client" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.PowerBI.Api.V2.PowerBIClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneReportInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; CloneReportInGroupWithHttpMessagesAsync (string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; CloneReportInGroupWithHttpMessagesAsync(string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.CloneReportInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.CloneReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloneReportInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.CloneReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;&#xA;override this.CloneReportInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.CloneReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="reports.CloneReportInGroupWithHttpMessagesAsync (groupId, reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.CloneReportInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.CloneReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;CloneReportInGroupWithHttpMessagesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.CloneReportRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneReportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; CloneReportWithHttpMessagesAsync (string reportKey, Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; CloneReportWithHttpMessagesAsync(string reportKey, class Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.CloneReportWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.CloneReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloneReportWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.CloneReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;&#xA;override this.CloneReportWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.CloneReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="reports.CloneReportWithHttpMessagesAsync (reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.CloneReportWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.CloneReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;CloneReportWithHttpMessagesAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.CloneReportRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteReportInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; DeleteReportInGroupWithHttpMessagesAsync (string groupId, string reportKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; DeleteReportInGroupWithHttpMessagesAsync(string groupId, string reportKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.DeleteReportInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteReportInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.DeleteReportInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="reports.DeleteReportInGroupWithHttpMessagesAsync (groupId, reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.DeleteReportInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;DeleteReportInGroupWithHttpMessagesAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteReportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; DeleteReportWithHttpMessagesAsync (string reportKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; DeleteReportWithHttpMessagesAsync(string reportKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.DeleteReportWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteReportWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.DeleteReportWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="reports.DeleteReportWithHttpMessagesAsync (reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.DeleteReportWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;DeleteReportWithHttpMessagesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reportKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportReportInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.IO.Stream&gt;&gt; ExportReportInGroupWithHttpMessagesAsync (string groupId, string reportKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class System.IO.Stream&gt;&gt; ExportReportInGroupWithHttpMessagesAsync(string groupId, string reportKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.ExportReportInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportReportInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.IO.Stream&gt;&gt;&#xA;override this.ExportReportInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.IO.Stream&gt;&gt;" Usage="reports.ExportReportInGroupWithHttpMessagesAsync (groupId, reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.ExportReportInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;ExportReportInGroupWithHttpMessagesAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.IO.Stream&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportReportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.IO.Stream&gt;&gt; ExportReportWithHttpMessagesAsync (string reportKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class System.IO.Stream&gt;&gt; ExportReportWithHttpMessagesAsync(string reportKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.ExportReportWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportReportWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.IO.Stream&gt;&gt;&#xA;override this.ExportReportWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.IO.Stream&gt;&gt;" Usage="reports.ExportReportWithHttpMessagesAsync (reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.ExportReportWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;ExportReportWithHttpMessagesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.IO.Stream&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reportKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenForCreateInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt; GenerateTokenForCreateInGroupWithHttpMessagesAsync (string groupId, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt; GenerateTokenForCreateInGroupWithHttpMessagesAsync(string groupId, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.GenerateTokenForCreateInGroupWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateTokenForCreateInGroupWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;&#xA;override this.GenerateTokenForCreateInGroupWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;" Usage="reports.GenerateTokenForCreateInGroupWithHttpMessagesAsync (groupId, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.GenerateTokenForCreateInGroupWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;GenerateTokenForCreateInGroupWithHttpMessagesAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenForCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt; GenerateTokenForCreateWithHttpMessagesAsync (Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt; GenerateTokenForCreateWithHttpMessagesAsync(class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.GenerateTokenForCreateWithHttpMessagesAsync(Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateTokenForCreateWithHttpMessagesAsync : Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;&#xA;override this.GenerateTokenForCreateWithHttpMessagesAsync : Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;" Usage="reports.GenerateTokenForCreateWithHttpMessagesAsync (requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.GenerateTokenForCreateWithHttpMessagesAsync(Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;GenerateTokenForCreateWithHttpMessagesAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt; GenerateTokenInGroupWithHttpMessagesAsync (string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt; GenerateTokenInGroupWithHttpMessagesAsync(string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.GenerateTokenInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateTokenInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;&#xA;override this.GenerateTokenInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;" Usage="reports.GenerateTokenInGroupWithHttpMessagesAsync (groupId, reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.GenerateTokenInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;GenerateTokenInGroupWithHttpMessagesAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateTokenWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt; GenerateTokenWithHttpMessagesAsync (string reportKey, Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt; GenerateTokenWithHttpMessagesAsync(string reportKey, class Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.GenerateTokenWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateTokenWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;&#xA;override this.GenerateTokenWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;" Usage="reports.GenerateTokenWithHttpMessagesAsync (reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.GenerateTokenWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;GenerateTokenWithHttpMessagesAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReportInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; GetReportInGroupWithHttpMessagesAsync (string groupId, string reportKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; GetReportInGroupWithHttpMessagesAsync(string groupId, string reportKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.GetReportInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetReportInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;&#xA;override this.GetReportInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="reports.GetReportInGroupWithHttpMessagesAsync (groupId, reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.GetReportInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;GetReportInGroupWithHttpMessagesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReportsInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt; GetReportsInGroupWithHttpMessagesAsync (string groupId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt; GetReportsInGroupWithHttpMessagesAsync(string groupId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.GetReportsInGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetReportsInGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt;&#xA;override this.GetReportsInGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt;" Usage="reports.GetReportsInGroupWithHttpMessagesAsync (groupId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.GetReportsInGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;GetReportsInGroupWithHttpMessagesAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReportsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt; GetReportsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt; GetReportsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.GetReportsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetReportsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt;&#xA;override this.GetReportsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt;" Usage="reports.GetReportsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.GetReportsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;GetReportsWithHttpMessagesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; GetReportWithHttpMessagesAsync (string reportKey, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; GetReportWithHttpMessagesAsync(string reportKey, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.GetReportWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetReportWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;&#xA;override this.GetReportWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="reports.GetReportWithHttpMessagesAsync (reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.GetReportWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;GetReportWithHttpMessagesAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reportKey">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebindReportInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; RebindReportInGroupWithHttpMessagesAsync (string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; RebindReportInGroupWithHttpMessagesAsync(string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.RebindReportInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.RebindReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RebindReportInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.RebindReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.RebindReportInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.RebindReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="reports.RebindReportInGroupWithHttpMessagesAsync (groupId, reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.RebindReportInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.RebindReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;RebindReportInGroupWithHttpMessagesAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.RebindReportRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebindReportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;object&gt;&gt; RebindReportWithHttpMessagesAsync (string reportKey, Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;object&gt;&gt; RebindReportWithHttpMessagesAsync(string reportKey, class Microsoft.PowerBI.Api.V2.Models.RebindReportRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.RebindReportWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.RebindReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RebindReportWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.RebindReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;&#xA;override this.RebindReportWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.RebindReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="reports.RebindReportWithHttpMessagesAsync (reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.RebindReportWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.RebindReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;RebindReportWithHttpMessagesAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.RebindReportRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReportContentInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; UpdateReportContentInGroupWithHttpMessagesAsync (string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; UpdateReportContentInGroupWithHttpMessagesAsync(string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.UpdateReportContentInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateReportContentInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;&#xA;override this.UpdateReportContentInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="reports.UpdateReportContentInGroupWithHttpMessagesAsync (groupId, reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.UpdateReportContentInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;UpdateReportContentInGroupWithHttpMessagesAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupId" Type="System.String" />
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupId">To be added.</param>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReportContentWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; UpdateReportContentWithHttpMessagesAsync (string reportKey, Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; UpdateReportContentWithHttpMessagesAsync(string reportKey, class Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.Reports.UpdateReportContentWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateReportContentWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;&#xA;override this.UpdateReportContentWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="reports.UpdateReportContentWithHttpMessagesAsync (reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.PowerBI.Api.V2.IReports.UpdateReportContentWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.PowerBI.Api.V2.Reports/&lt;UpdateReportContentWithHttpMessagesAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reportKey" Type="System.String" />
        <Parameter Name="requestParameters" Type="Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reportKey">To be added.</param>
        <param name="requestParameters">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>