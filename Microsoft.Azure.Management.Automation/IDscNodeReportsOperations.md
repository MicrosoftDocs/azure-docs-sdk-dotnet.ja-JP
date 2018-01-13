<Type Name="IDscNodeReportsOperations" FullName="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations">
  <TypeSignature Language="C#" Value="public interface IDscNodeReportsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDscNodeReportsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDscNodeReportsOperations" />
  <TypeSignature Language="F#" Value="type IDscNodeReportsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            サービスのノードのレポートを操作します。  (詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, Guid nodeId, Guid reportId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Guid reportId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.GetAsync(System.String,System.String,System.Guid,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Guid * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt;" Usage="iDscNodeReportsOperations.GetAsync (resourceGroupName, automationAccount, nodeId, reportId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="reportId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="nodeId">
            Dsc ノードの id。
            </param>
        <param name="reportId">
            レポートの id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ノード id とレポートの id では、Dsc ノード レポート データを取得します。 (詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)
            </summary>
        <returns>
            Get 応答モデル dsc ノード レポートを操作します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt; GetContentAsync (string resourceGroupName, string automationAccount, Guid nodeId, Guid reportId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt; GetContentAsync(string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Guid reportId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.GetContentAsync(System.String,System.String,System.Guid,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetContentAsync : string * string * Guid * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt;" Usage="iDscNodeReportsOperations.GetContentAsync (resourceGroupName, automationAccount, nodeId, reportId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="reportId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="nodeId">
            Dsc ノードの id。
            </param>
        <param name="reportId">
            レポートの id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ノード id とレポートの id での Dsc ノード レポートを取得します。 (詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)
            </summary>
        <returns>
            ノード レポート コンテンツの取得操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;" Usage="iDscNodeReportsOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="parameters">
            一覧表示操作に指定するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ノード id とレポートの id では、Dsc ノード レポート リストを取得します。 (詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)
            </summary>
        <returns>
            一覧の dsc ノードの操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;" Usage="iDscNodeReportsOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            次の項目のセットを取得するリンクです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ノード id とレポートの id では、Dsc ノード レポート リストを取得します。 (詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)
            </summary>
        <returns>
            一覧の dsc ノードの操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>