<Type Name="IBackUpOperations" FullName="Microsoft.Azure.Management.BackupServices.IBackUpOperations">
  <TypeSignature Language="C#" Value="public interface IBackUpOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackUpOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IBackUpOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackUpOperations" />
  <TypeSignature Language="F#" Value="type IBackUpOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Azure Backup の拡張機能のバックアップ操作の定義。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TriggerBackUpAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerBackUpAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerBackUpAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IBackUpOperations.TriggerBackUpAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TriggerBackUpAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iBackUpOperations.TriggerBackUpAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            ヘッダーのパラメーターを要求します。
            </param>
        <param name="containerName">To be added.</param>
        <param name="itemName">To be added.</param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            バックアップ、AzureBackUpItem です。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>