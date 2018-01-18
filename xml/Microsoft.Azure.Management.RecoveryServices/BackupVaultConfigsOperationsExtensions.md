<Type Name="BackupVaultConfigsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupVaultConfigsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupVaultConfigsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupVaultConfigsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupVaultConfigsOperationsExtensions = class" />
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
            <span data-ttu-id="3c048-101">BackupVaultConfigsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="3c048-101">Extension methods for BackupVaultConfigsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig Get (this Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig Get(class Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupVaultConfigsOperations, resourceGroupName As String, vaultName As String) As BackupVaultConfig" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig" Usage="Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions.Get (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3c048-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3c048-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3c048-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="3c048-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="3c048-104">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3c048-104">The name of the recovery services vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3c048-105">フェッチ コンテナーに設定します。</span><span class="sxs-lookup"><span data-stu-id="3c048-105">Fetches vault config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions.GetAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3c048-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3c048-106">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3c048-107">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="3c048-107">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="3c048-108">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3c048-108">The name of the recovery services vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3c048-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3c048-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3c048-110">フェッチ コンテナーに設定します。</span><span class="sxs-lookup"><span data-stu-id="3c048-110">Fetches vault config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig Update (this Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig backupVaultConfig);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig Update(class Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig backupVaultConfig) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions.Update(Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig -&gt; Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig" Usage="Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions.Update (operations, resourceGroupName, vaultName, backupVaultConfig)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="backupVaultConfig" Type="Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3c048-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3c048-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3c048-112">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="3c048-112">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="3c048-113">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3c048-113">The name of the recovery services vault.</span></span>
            </param>
        <param name="backupVaultConfig">
            <span data-ttu-id="3c048-114">バックアップ コンテナーの構成。</span><span class="sxs-lookup"><span data-stu-id="3c048-114">Backup vault config.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3c048-115">更新プログラムには、構成モデルの種類が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="3c048-115">Updates vault config model type.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig&gt; UpdateAsync (this Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig backupVaultConfig, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig&gt; UpdateAsync(class Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig backupVaultConfig, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations * string * string * Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions.UpdateAsync (operations, resourceGroupName, vaultName, backupVaultConfig, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.BackupVaultConfigsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.IBackupVaultConfigsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="backupVaultConfig" Type="Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3c048-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3c048-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3c048-117">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="3c048-117">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="3c048-118">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="3c048-118">The name of the recovery services vault.</span></span>
            </param>
        <param name="backupVaultConfig">
            <span data-ttu-id="3c048-119">バックアップ コンテナーの構成。</span><span class="sxs-lookup"><span data-stu-id="3c048-119">Backup vault config.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3c048-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3c048-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3c048-121">更新プログラムには、構成モデルの種類が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="3c048-121">Updates vault config model type.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>