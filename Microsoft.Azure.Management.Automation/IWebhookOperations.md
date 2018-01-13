<Type Name="IWebhookOperations" FullName="Microsoft.Azure.Management.Automation.IWebhookOperations">
  <TypeSignature Language="C#" Value="public interface IWebhookOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWebhookOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IWebhookOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWebhookOperations" />
  <TypeSignature Language="F#" Value="type IWebhookOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Automation webhook のサービス操作。  (詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IWebhookOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt;" Usage="iWebhookOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters" />
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
            Webhook の作成または更新プログラムのパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Webhook の名前によって識別される webhook を作成します。  (詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)
            </summary>
        <returns>
            作成または更新の webhook 操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string webhookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IWebhookOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iWebhookOperations.DeleteAsync (resourceGroupName, automationAccount, webhookName, cancellationToken)" />
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
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="webhookName">
            Webhook の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            名前で、webhook を削除します。  (詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateUriAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt; GenerateUriAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt; GenerateUriAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IWebhookOperations.GenerateUriAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateUriAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt;" Usage="iWebhookOperations.GenerateUriAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Webhook の作成に使用するための Uri を生成します。  (詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)
            </summary>
        <returns>
            Webhook の応答モデルでは、uri の応答を取得します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string webhookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string webhookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IWebhookOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;" Usage="iWebhookOperations.GetAsync (resourceGroupName, automationAccount, webhookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="webhookName">
            Webhook の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Webhook の名前によって識別される webhook を取得します。  (詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)
            </summary>
        <returns>
            Webhook の取得操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IWebhookOperations.ListAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;" Usage="iWebhookOperations.ListAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="runbookName">
            Automation runbook の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Webhook の一覧を取得します。  (詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)
            </summary>
        <returns>
            一覧の webhook 操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IWebhookOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;" Usage="iWebhookOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;</ReturnType>
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
            Webhook の次の一覧を取得します。  (詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)
            </summary>
        <returns>
            一覧の webhook 操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IWebhookOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;" Usage="iWebhookOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters" />
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
            Webhook の更新プログラムのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Webhook の webhook 名によって識別される修正プログラムを適用します。  (詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)
            </summary>
        <returns>
            Webhook の取得操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>