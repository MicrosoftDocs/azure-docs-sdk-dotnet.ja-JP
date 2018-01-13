<Type Name="BackupPolicyOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupPolicyOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupPolicyOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupPolicyOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupPolicyOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            これは、StorSimple のオブジェクトを管理する rest ベースの API
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreatingBackupPolicy">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreatingBackupPolicy (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreatingBackupPolicy(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicy(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingBackupPolicy : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicy (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupPolicy">
            必須。 パラメーターは、バックアップ ポリシーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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
    <Member MemberName="BeginCreatingBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupPolicyAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupPolicyAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicyAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingBackupPolicyAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicyAsync (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupPolicy">
            必須。 パラメーターは、バックアップ ポリシーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeleting (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 削除するバックアップ ポリシーの ID。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeletingAsync (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 削除するバックアップ ポリシーの ID。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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
    <Member MemberName="BeginUpdatingBackupPolicy">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdatingBackupPolicy (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdatingBackupPolicy(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicy(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdatingBackupPolicy : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicy (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 更新するバックアップ ポリシーの ID。
            </param>
        <param name="policyInfo">
            必須。 パラメーターは、バックアップ ポリシーの更新操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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
    <Member MemberName="BeginUpdatingBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdatingBackupPolicyAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdatingBackupPolicyAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicyAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdatingBackupPolicyAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicyAsync (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 更新するバックアップ ポリシーの ID。
            </param>
        <param name="policyInfo">
            必須。 パラメーターは、バックアップ ポリシーの更新操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Create (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupPolicy">
            必須。 パラメーターは、バックアップ ポリシーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.CreateAsync (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupPolicy">
            必須。 パラメーターは、バックアップ ポリシーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Delete (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 削除するバックアップ ポリシーの ID。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.DeleteAsync (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 削除するバックアップ ポリシーの ID。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBackupPolicyDetailsByName">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse GetBackupPolicyDetailsByName (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse GetBackupPolicyDetailsByName(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByName(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetBackupPolicyDetailsByName : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByName (operations, deviceId, policyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyName">
            必須。 バックアップ ポリシーの詳細をフェッチするポリシーの名前。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            バックアップ ポリシーの一覧について応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBackupPolicyDetailsByNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt; GetBackupPolicyDetailsByNameAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt; GetBackupPolicyDetailsByNameAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByNameAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetBackupPolicyDetailsByNameAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByNameAsync (operations, deviceId, policyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyName">
            必須。 バックアップ ポリシーの詳細をフェッチするポリシーの名前。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            バックアップ ポリシーの一覧について応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse List (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse List(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.List(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.List (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            バックアップ ポリシーの一覧について応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt; ListAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.ListAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            バックアップ ポリシーの一覧について応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Update(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Update (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 更新するバックアップ ポリシーの ID。
            </param>
        <param name="policyInfo">
            必須。 パラメーターは、バックアップ ポリシーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.UpdateAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.UpdateAsync (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 更新するバックアップ ポリシーの ID。
            </param>
        <param name="policyInfo">
            必須。 パラメーターは、バックアップ ポリシーの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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