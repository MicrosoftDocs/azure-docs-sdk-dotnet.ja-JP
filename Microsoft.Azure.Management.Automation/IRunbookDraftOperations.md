<Type Name="IRunbookDraftOperations" FullName="Microsoft.Azure.Management.Automation.IRunbookDraftOperations">
  <TypeSignature Language="C#" Value="public interface IRunbookDraftOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRunbookDraftOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IRunbookDraftOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRunbookDraftOperations" />
  <TypeSignature Language="F#" Value="type IRunbookDraftOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Automation runbook の下書きのサービス操作。  (詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginPublishAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginPublishAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginPublishAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.BeginPublishAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginPublishAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.BeginPublishAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
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
            Runbook の発行操作に指定するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Runbook 名によって識別される runbook を取得します。  (詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.BeginUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.BeginUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
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
            Runbook ドラフト パラメーターを変更しています。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            その内容として runbookStream で runbook のドラフトを更新します。  (詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateGraphAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateGraphAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateGraphAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.BeginUpdateGraphAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateGraphAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.BeginUpdateGraphAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
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
            Runbook ドラフト パラメーターを変更しています。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            その内容として runbookStream で runbook のドラフトを更新します。  (詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.ContentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContentAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;" Usage="iRunbookDraftOperations.ContentAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;</ReturnType>
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
            Runbook の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Runbook 名によって識別される runbook の下書きのコンテンツを取得します。
            (詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)
            </summary>
        <returns>
            Runbook のコンテンツ操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt;" Usage="iRunbookDraftOperations.GetAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt;</ReturnType>
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
            Runbook の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Runbook 名によって識別される runbook の下書きを取得します。  (詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)
            </summary>
        <returns>
            Runbook の下書きの取得操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; PublishAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; PublishAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.PublishAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PublishAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.PublishAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
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
            Runbook の発行操作に指定するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Runbook 名によって識別される runbook を取得します。  (詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndoEditAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt; UndoEditAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt; UndoEditAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.UndoEditAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UndoEditAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt;" Usage="iRunbookDraftOperations.UndoEditAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt;</ReturnType>
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
            Runbook の名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Runbook 名によって識別される runbook を取得します。  (詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)
            </summary>
        <returns>
            Undoedit runbook の操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.UpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.UpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
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
            Runbook ドラフト パラメーターを変更しています。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            その内容として runbookStream で runbook のドラフトを更新します。  (詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateGraphAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateGraphAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateGraphAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.UpdateGraphAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateGraphAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.UpdateGraphAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
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
            Runbook ドラフト パラメーターを変更しています。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            その内容として runbookStream で runbook のドラフトを更新します。  (詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>