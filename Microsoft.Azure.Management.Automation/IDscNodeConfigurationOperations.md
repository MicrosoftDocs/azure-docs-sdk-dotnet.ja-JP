<Type Name="IDscNodeConfigurationOperations" FullName="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations">
  <TypeSignature Language="C#" Value="public interface IDscNodeConfigurationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDscNodeConfigurationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDscNodeConfigurationOperations" />
  <TypeSignature Language="F#" Value="type IDscNodeConfigurationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Automation dsc ノード構成のサービス操作。  (詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;" Usage="iDscNodeConfigurationOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters" />
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
            構成の作成または更新パラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ノード構成名で識別されるノードの構成を作成します。  (詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)
            </summary>
        <returns>
            Get Dsc ノード構成の操作の応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string nodeConfigurationName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string nodeConfigurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDscNodeConfigurationOperations.DeleteAsync (resourceGroupName, automationAccount, nodeConfigurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="nodeConfigurationName">
            Dsc ノード構成名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ノードの構成での Dsc ノード構成を削除します。  (詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string nodeConfigurationName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string nodeConfigurationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;" Usage="iDscNodeConfigurationOperations.GetAsync (resourceGroupName, automationAccount, nodeConfigurationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="nodeConfigurationName">
            Dsc ノード構成名。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ノードの構成での Dsc ノード構成を取得します。  (詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)
            </summary>
        <returns>
            Get Dsc ノード構成の操作の応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;" Usage="iDscNodeConfigurationOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters" />
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
            Dsc ノード構成の一覧を取得します。  (詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)
            </summary>
        <returns>
            一覧のジョブ操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;" Usage="iDscNodeConfigurationOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;</ReturnType>
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
            Dsc ノード configrations の次の一覧を取得します。  (詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)
            </summary>
        <returns>
            一覧のジョブ操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>