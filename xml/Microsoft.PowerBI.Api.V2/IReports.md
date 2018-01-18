<Type Name="IReports" FullName="Microsoft.PowerBI.Api.V2.IReports">
  <TypeSignature Language="C#" Value="public interface IReports" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReports" />
  <TypeSignature Language="DocId" Value="T:Microsoft.PowerBI.Api.V2.IReports" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReports" />
  <TypeSignature Language="F#" Value="type IReports = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
    <AssemblyVersion>2.0.3.17253</AssemblyVersion>
    <AssemblyVersion>2.0.8.17320</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloneReportInGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; CloneReportInGroupWithHttpMessagesAsync (string groupId, string reportKey, Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt; CloneReportInGroupWithHttpMessagesAsync(string groupId, string reportKey, class Microsoft.PowerBI.Api.V2.Models.CloneReportRequest requestParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.CloneReportInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.CloneReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloneReportInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.CloneReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="iReports.CloneReportInGroupWithHttpMessagesAsync (groupId, reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.CloneReportWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.CloneReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloneReportWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.CloneReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="iReports.CloneReportWithHttpMessagesAsync (reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.DeleteReportInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteReportInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="iReports.DeleteReportInGroupWithHttpMessagesAsync (groupId, reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.DeleteReportWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteReportWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="iReports.DeleteReportWithHttpMessagesAsync (reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.ExportReportInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportReportInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.IO.Stream&gt;&gt;" Usage="iReports.ExportReportInGroupWithHttpMessagesAsync (groupId, reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.ExportReportWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportReportWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;System.IO.Stream&gt;&gt;" Usage="iReports.ExportReportWithHttpMessagesAsync (reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.GenerateTokenForCreateInGroupWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateTokenForCreateInGroupWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;" Usage="iReports.GenerateTokenForCreateInGroupWithHttpMessagesAsync (groupId, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.GenerateTokenForCreateWithHttpMessagesAsync(Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateTokenForCreateWithHttpMessagesAsync : Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;" Usage="iReports.GenerateTokenForCreateWithHttpMessagesAsync (requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.GenerateTokenInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateTokenInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;" Usage="iReports.GenerateTokenInGroupWithHttpMessagesAsync (groupId, reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.GenerateTokenWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateTokenWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.GenerateTokenRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.EmbedToken&gt;&gt;" Usage="iReports.GenerateTokenWithHttpMessagesAsync (reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.GetReportInGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetReportInGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="iReports.GetReportInGroupWithHttpMessagesAsync (groupId, reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.GetReportsInGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetReportsInGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt;" Usage="iReports.GetReportsInGroupWithHttpMessagesAsync (groupId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.GetReportsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetReportsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.ODataResponseListReport&gt;&gt;" Usage="iReports.GetReportsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.GetReportWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetReportWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="iReports.GetReportWithHttpMessagesAsync (reportKey, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.RebindReportInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.RebindReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RebindReportInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.RebindReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="iReports.RebindReportInGroupWithHttpMessagesAsync (groupId, reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.RebindReportWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.RebindReportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RebindReportWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.RebindReportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;obj&gt;&gt;" Usage="iReports.RebindReportWithHttpMessagesAsync (reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.3.17253</AssemblyVersion>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.UpdateReportContentInGroupWithHttpMessagesAsync(System.String,System.String,Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateReportContentInGroupWithHttpMessagesAsync : string * string * Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="iReports.UpdateReportContentInGroupWithHttpMessagesAsync (groupId, reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.PowerBI.Api.V2.IReports.UpdateReportContentWithHttpMessagesAsync(System.String,Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateReportContentWithHttpMessagesAsync : string * Microsoft.PowerBI.Api.V2.Models.UpdateReportContentRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.PowerBI.Api.V2.Models.Report&gt;&gt;" Usage="iReports.UpdateReportContentWithHttpMessagesAsync (reportKey, requestParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.PowerBI.Api</AssemblyName>
        <AssemblyVersion>2.0.8.17320</AssemblyVersion>
      </AssemblyInfo>
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