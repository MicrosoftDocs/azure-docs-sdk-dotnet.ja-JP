<Type Name="IBackupPolicyOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations">
  <TypeSignature Language="C#" Value="public interface IBackupPolicyOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupPolicyOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupPolicyOperations" />
  <TypeSignature Language="F#" Value="type IBackupPolicyOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            バックアップ ポリシーに関連するすべての操作
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreatingBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupPolicyAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupPolicyAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.BeginCreatingBackupPolicyAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreatingBackupPolicyAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupPolicyOperations.BeginCreatingBackupPolicyAsync (deviceId, backupPolicy, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupPolicy">
            パラメーターは、バックアップ ポリシーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            BeginCreatingBackupPolicy 操作は、特定のスケジュールを指定したこのボリュームの新しいバックアップ ポリシーを作成します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.BeginDeletingAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeletingAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupPolicyOperations.BeginDeletingAsync (deviceId, policyId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            削除するバックアップ ポリシーの ID。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            提供される policyId によって表されるバックアップ ポリシーの削除を開始します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdatingBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdatingBackupPolicyAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdatingBackupPolicyAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.BeginUpdatingBackupPolicyAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdatingBackupPolicyAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupPolicyOperations.BeginUpdatingBackupPolicyAsync (deviceId, policyId, policyInfo, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            更新するバックアップ ポリシーの ID。
            </param>
        <param name="policyInfo">
            パラメーターは、バックアップ ポリシーの更新操作に指定します。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            BeginUpdatingBackupPolicy 操作では、指定されたスケジュールで指定したこのボリュームの policyId によって表されるバックアップ ポリシーを更新します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.CreateAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupPolicyOperations.CreateAsync (deviceId, backupPolicy, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupPolicy">
            パラメーターは、バックアップ ポリシーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.DeleteAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupPolicyOperations.DeleteAsync (deviceId, policyId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            削除するバックアップ ポリシーの ID。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBackupPolicyDetailsByNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt; GetBackupPolicyDetailsByNameAsync (string deviceId, string policyName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt; GetBackupPolicyDetailsByNameAsync(string deviceId, string policyName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.GetBackupPolicyDetailsByNameAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetBackupPolicyDetailsByNameAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt;" Usage="iBackupPolicyOperations.GetBackupPolicyDetailsByNameAsync (deviceId, policyName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyName">
            バックアップ ポリシーの詳細をフェッチするポリシーの名前。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            バックアップ ポリシーの一覧について応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt; ListAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt; ListAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.ListAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt;" Usage="iBackupPolicyOperations.ListAsync (deviceId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            呼び出しの作成対象のデバイス id です。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            バックアップ ポリシーの一覧について応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.UpdateAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupPolicyOperations.UpdateAsync (deviceId, policyId, policyInfo, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            更新するバックアップ ポリシーの ID。
            </param>
        <param name="policyInfo">
            パラメーターは、バックアップ ポリシーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>