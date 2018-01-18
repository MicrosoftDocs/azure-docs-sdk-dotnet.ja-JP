<Type Name="BackupStorageConfigsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupStorageConfigsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupStorageConfigsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupStorageConfigsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupStorageConfigsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bd518-101">BackupStorageConfigsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="bd518-101">Extension methods for BackupStorageConfigsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig Get (this Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig Get(class Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupStorageConfigsOperations, resourceGroupName As String, vaultName As String) As BackupStorageConfig" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig" Usage="Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.Get (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bd518-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="bd518-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bd518-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="bd518-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="bd518-104">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="bd518-104">The name of the recovery services vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bd518-105">リソースの記憶域構成をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="bd518-105">Fetches resource storage config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.GetAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bd518-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="bd518-106">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bd518-107">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="bd518-107">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="bd518-108">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="bd518-108">The name of the recovery services vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bd518-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bd518-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bd518-110">リソースの記憶域構成をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="bd518-110">Fetches resource storage config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static void Update (this Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig backupStorageConfig);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Update(class Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig backupStorageConfig) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.Update(Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.Update (operations, resourceGroupName, vaultName, backupStorageConfig)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="backupStorageConfig" Type="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bd518-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="bd518-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bd518-112">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="bd518-112">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="bd518-113">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="bd518-113">The name of the recovery services vault.</span></span>
            </param>
        <param name="backupStorageConfig">
            <span data-ttu-id="bd518-114">バックアップ記憶域の構成。</span><span class="sxs-lookup"><span data-stu-id="bd518-114">Backup storage config.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bd518-115">更新プログラムには、ストレージ モデルの種類が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="bd518-115">Updates vault storage model type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateAsync (this Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig backupStorageConfig, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateAsync(class Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig backupStorageConfig, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions.UpdateAsync (operations, resourceGroupName, vaultName, backupStorageConfig, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.BackupStorageConfigsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupStorageConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="backupStorageConfig" Type="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bd518-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="bd518-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bd518-117">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="bd518-117">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="bd518-118">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="bd518-118">The name of the recovery services vault.</span></span>
            </param>
        <param name="backupStorageConfig">
            <span data-ttu-id="bd518-119">バックアップ記憶域の構成。</span><span class="sxs-lookup"><span data-stu-id="bd518-119">Backup storage config.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bd518-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bd518-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bd518-121">更新プログラムには、ストレージ モデルの種類が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="bd518-121">Updates vault storage model type.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>