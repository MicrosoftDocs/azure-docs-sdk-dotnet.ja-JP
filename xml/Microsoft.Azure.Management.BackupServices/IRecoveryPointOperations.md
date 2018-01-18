<Type Name="IRecoveryPointOperations" FullName="Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations">
  <TypeSignature Language="C#" Value="public interface IRecoveryPointOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecoveryPointOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecoveryPointOperations" />
  <TypeSignature Language="F#" Value="type IRecoveryPointOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="845bb-101">Azure Backup の拡張機能の回復ポイントの操作の定義。</span><span class="sxs-lookup"><span data-stu-id="845bb-101">Definition of Recovery Point operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt; GetAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt; GetAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt;" Usage="iRecoveryPointOperations.GetAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="845bb-102">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="845bb-102">Request header parameters.</span></span>
            </param>
        <param name="containerName">To be added.</param>
        <param name="itemName">To be added.</param>
        <param name="recoveryPointName">To be added.</param>
        <param name="cancellationToken">
            <span data-ttu-id="845bb-103">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="845bb-103">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="845bb-104">回復ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="845bb-104">Get the recovery point.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="845bb-105">CSMRecoveryPointGetOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="845bb-105">The definition of a CSMRecoveryPointGetOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt; ListAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt; ListAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt;" Usage="iRecoveryPointOperations.ListAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt;</ReturnType>
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
            <span data-ttu-id="845bb-106">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="845bb-106">Request header parameters.</span></span>
            </param>
        <param name="containerName">To be added.</param>
        <param name="itemName">To be added.</param>
        <param name="cancellationToken">
            <span data-ttu-id="845bb-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="845bb-107">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="845bb-108">すべての回復ポイントの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="845bb-108">Get the list of all recovery points.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="845bb-109">CSMRecoveryPointListOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="845bb-109">The definition of a CSMRecoveryPointListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>