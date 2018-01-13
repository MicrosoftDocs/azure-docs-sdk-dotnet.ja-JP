<Type Name="RestoreOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RestoreOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RestoreOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RestoreOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RestoreOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TriggerResotre">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse TriggerResotre (this Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse TriggerResotre(class Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, class Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotre(Microsoft.Azure.Management.BackupServices.IRestoreOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest)" />
      <MemberSignature Language="F#" Value="static member TriggerResotre : Microsoft.Azure.Management.BackupServices.IRestoreOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotre (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IRestoreOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IRestoreOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <param name="containerName">
            省略可能。
            </param>
        <param name="itemName">
            省略可能。
            </param>
        <param name="recoveryPointName">
            省略可能。
            </param>
        <param name="parameters">
            省略可能。
            </param>
        <summary>
            Azure BackUpItem を復元します。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerResotreAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerResotreAsync (this Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerResotreAsync(class Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, class Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotreAsync(Microsoft.Azure.Management.BackupServices.IRestoreOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest)" />
      <MemberSignature Language="F#" Value="static member TriggerResotreAsync : Microsoft.Azure.Management.BackupServices.IRestoreOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotreAsync (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IRestoreOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IRestoreOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <param name="containerName">
            省略可能。
            </param>
        <param name="itemName">
            省略可能。
            </param>
        <param name="recoveryPointName">
            省略可能。
            </param>
        <param name="parameters">
            省略可能。
            </param>
        <summary>
            Azure BackUpItem を復元します。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>