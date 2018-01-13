<Type Name="IHybridRunbookWorkerGroupOperations" FullName="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations">
  <TypeSignature Language="C#" Value="public interface IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="F#" Value="type IHybridRunbookWorkerGroupOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Automation hybrid runbook worker グループのサービス操作。  (詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.DeleteAsync (resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, cancellationToken)" />
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
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前です。
            </param>
        <param name="hybridRunbookWorkerGroupName">
            ハイブリッド runbook worker グループ名
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Hybrid runbook worker グループを削除します。  (詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.GetAsync (resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="hybridRunbookWorkerGroupName">
            ハイブリッド runbook worker グループ名
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Hybrid runbook worker グループを取得します。  (詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)
            </summary>
        <returns>
            Get ハイブリッド runbook worker グループの操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ハイブリッド runbook worker グループの一覧を取得します。  (詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)
            </summary>
        <returns>
            リストのハイブリッド runbook worker グループの応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;</ReturnType>
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
            ハイブリッド runbook worker グループの [次へ] の一覧を取得します。  (詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)
            </summary>
        <returns>
            リストのハイブリッド runbook worker グループの応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.PatchAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * string * Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.PatchAsync (resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="hybridRunbookWorkerGroupName">
            ハイブリッド runbook worker グループ名
            </param>
        <param name="parameters">
            Hybrid runbook worker グループ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Hybrid runbook worker グループを更新します。  (詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)
            </summary>
        <returns>
            修正プログラム ハイブリッド runbook worker グループの操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>