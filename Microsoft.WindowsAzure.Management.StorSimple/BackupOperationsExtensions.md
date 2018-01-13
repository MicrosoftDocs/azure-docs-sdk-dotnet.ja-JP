<Type Name="BackupOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupOperationsExtensions = class" />
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
    <Member MemberName="BeginCreatingBackup">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreatingBackup (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreatingBackup(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginCreatingBackup(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingBackup : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginCreatingBackup (operations, deviceId, policyId, backupRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 呼び出しの行われたポリシーの id。
            </param>
        <param name="backupRequest">
            必須。 パラメーターは、バックアップを開始操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            PolicyId と backupRequest 指定のバックアップ操作を開始します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingBackupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginCreatingBackupAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingBackupAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginCreatingBackupAsync (operations, deviceId, policyId, backupRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 呼び出しの行われたポリシーの id。
            </param>
        <param name="backupRequest">
            必須。 パラメーターは、バックアップを開始操作に指定します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            PolicyId と backupRequest 指定のバックアップ操作を開始します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginDeleting (operations, deviceId, backupSetId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupSetId">
            必須。 バックアップ セットの ID を削除します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            指定された backSetId によって表されるバックアップ セットの削除を開始します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginDeletingAsync (operations, deviceId, backupSetId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupSetId">
            必須。 バックアップ セットの ID を削除します。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            指定された backSetId によって表されるバックアップ セットの削除を開始します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestoring">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginRestoring (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginRestoring(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginRestoring(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginRestoring : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginRestoring (operations, deviceId, backupDetailsForRestore, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupDetailsForRestore">
            必須。 復元するバックアップの詳細。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            バックアップ セットの復元を開始します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestoringAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginRestoringAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginRestoringAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginRestoringAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginRestoringAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginRestoringAsync (operations, deviceId, backupDetailsForRestore, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupDetailsForRestore">
            必須。 復元するバックアップの詳細。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            バックアップ セットの復元を開始します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Create (operations, deviceId, policyId, backupRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 呼び出しの行われたポリシーの id。
            </param>
        <param name="backupRequest">
            必須。 パラメーターは、バックアップを開始操作に指定します。
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
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.CreateAsync (operations, deviceId, policyId, backupRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="policyId">
            必須。 呼び出しの行われたポリシーの id。
            </param>
        <param name="backupRequest">
            必須。 パラメーターは、バックアップを開始操作に指定します。
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
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Delete (operations, deviceId, backupSetId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupSetId">
            必須。 バックアップ セットの ID を削除します。
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
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.DeleteAsync (operations, deviceId, backupSetId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupSetId">
            必須。 バックアップ セットの ID を削除します。
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * string * string * string * string * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Get (operations, deviceId, filterType, isAllSelected, filterValue, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="filterType" Type="System.String" />
        <Parameter Name="isAllSelected" Type="System.String" />
        <Parameter Name="filterValue" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="filterType">
            省略可能。 場合 isAllSelected = true の場合、そのボリュームまたは BackupPolicy をここで指定
            </param>
        <param name="isAllSelected">
            必須。 ボリュームまたは BackupPolicy またはその両方を取得するには
            </param>
        <param name="filterValue">
            省略可能。 場合 isAllSelected = true、VolumeId または BackupPolicy をここで指定し、
            </param>
        <param name="startTime">
            省略可能。 バックアップ セットをフィルター処理の開始時刻
            </param>
        <param name="endTime">
            省略可能。 バックアップ セットをフィルター処理の終了時刻
            </param>
        <param name="skip">
            省略可能。 改ページの一部としてスキップする要素の数
            </param>
        <param name="top">
            省略可能。 現在のページで取得する要素の数
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            バックアップ セットの一覧について応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * string * string * string * string * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.GetAsync (operations, deviceId, filterType, isAllSelected, filterValue, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="filterType" Type="System.String" />
        <Parameter Name="isAllSelected" Type="System.String" />
        <Parameter Name="filterValue" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="filterType">
            省略可能。 場合 isAllSelected = true の場合、そのボリュームまたは BackupPolicy をここで指定
            </param>
        <param name="isAllSelected">
            必須。 ボリュームまたは BackupPolicy またはその両方を取得するには
            </param>
        <param name="filterValue">
            省略可能。 場合 isAllSelected = true、VolumeId または BackupPolicy をここで指定し、
            </param>
        <param name="startTime">
            省略可能。 バックアップ セットをフィルター処理の開始時刻
            </param>
        <param name="endTime">
            省略可能。 バックアップ セットをフィルター処理の終了時刻
            </param>
        <param name="skip">
            省略可能。 改ページの一部としてスキップする要素の数
            </param>
        <param name="top">
            省略可能。 現在のページで取得する要素の数
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            バックアップ セットの一覧について応答モデルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restore">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Restore (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Restore(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Restore(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Restore : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Restore (operations, deviceId, backupDetailsForRestore, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupDetailsForRestore">
            必須。 復元するバックアップの詳細。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            バックアップ セットを復元します。
            </summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; RestoreAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; RestoreAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.RestoreAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member RestoreAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.RestoreAsync (operations, deviceId, backupDetailsForRestore, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations への参照。
            </param>
        <param name="deviceId">
            必須。 呼び出しの作成対象のデバイス id です。
            </param>
        <param name="backupDetailsForRestore">
            必須。 復元するバックアップの詳細。
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>
            バックアップ セットを復元します。
            </summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>