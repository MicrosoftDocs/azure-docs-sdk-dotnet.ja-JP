<Type Name="BackupResourceStorageConfigsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupResourceStorageConfigsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupResourceStorageConfigsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupResourceStorageConfigsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupResourceStorageConfigsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fc662-101">BackupResourceStorageConfigsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="fc662-101">Extension methods for BackupResourceStorageConfigsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations operations, string vaultName, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations operations, string vaultName, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupResourceStorageConfigsOperations, vaultName As String, resourceGroupName As String) As BackupResourceConfigResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions.Get (operations, vaultName, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fc662-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fc662-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="fc662-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="fc662-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fc662-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="fc662-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fc662-105">リソースの記憶域構成をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="fc662-105">Fetches resource storage config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations operations, string vaultName, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations operations, string vaultName, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fc662-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fc662-106">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="fc662-107">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="fc662-107">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fc662-108">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="fc662-108">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fc662-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc662-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fc662-110">リソースの記憶域構成をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="fc662-110">Fetches resource storage config.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static void Update (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations operations, string vaultName, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Update(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations operations, string vaultName, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions.Update(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Update (operations As IBackupResourceStorageConfigsOperations, vaultName As String, resourceGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions.Update (operations, vaultName, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fc662-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fc662-111">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="fc662-112">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="fc662-112">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fc662-113">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="fc662-113">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fc662-114">更新プログラムには、ストレージ モデルの種類が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="fc662-114">Updates vault storage model type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations operations, string vaultName, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations operations, string vaultName, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions.UpdateAsync (operations, vaultName, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.BackupResourceStorageConfigsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IBackupResourceStorageConfigsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fc662-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="fc662-115">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="fc662-116">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="fc662-116">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fc662-117">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="fc662-117">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fc662-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc662-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fc662-119">更新プログラムには、ストレージ モデルの種類が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="fc662-119">Updates vault storage model type.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>