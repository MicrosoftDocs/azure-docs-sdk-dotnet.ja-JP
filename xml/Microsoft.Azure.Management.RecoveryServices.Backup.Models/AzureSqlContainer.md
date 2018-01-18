<Type Name="AzureSqlContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer">
  <TypeSignature Language="C#" Value="public class AzureSqlContainer : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSqlContainer extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSqlContainer&#xA;Inherits ProtectionContainer" />
  <TypeSignature Language="F#" Value="type AzureSqlContainer = class&#xA;    inherit ProtectionContainer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="13d23-101">Azure の Sql ワークロードに固有のコンテナーです。</span><span class="sxs-lookup"><span data-stu-id="13d23-101">Azure Sql workload-specific container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="13d23-102">AzureSqlContainer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13d23-102">Initializes a new instance of the AzureSqlContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer : string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="registrationStatus" Type="System.String" />
        <Parameter Name="healthStatus" Type="System.String" />
        <Parameter Name="containerType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="friendlyName"><span data-ttu-id="13d23-103">コンテナーのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="13d23-103">Friendly name of the container.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="13d23-104">コンテナーのバックアップ managemenent の型。</span><span class="sxs-lookup"><span data-stu-id="13d23-104">Type of backup managemenent for the container.</span></span> <span data-ttu-id="13d23-105">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="13d23-105">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="13d23-106">Recovery Services コンテナーのコンテナーの登録の状態です。</span><span class="sxs-lookup"><span data-stu-id="13d23-106">Status of registration of the container with the Recovery Services Vault.</span></span></param>
        <param name="healthStatus"><span data-ttu-id="13d23-107">コンテナーの正常性の状態です。</span><span class="sxs-lookup"><span data-stu-id="13d23-107">Status of health of the container.</span></span></param>
        <param name="containerType"><span data-ttu-id="13d23-108">コンテナーの型。</span><span class="sxs-lookup"><span data-stu-id="13d23-108">Type of the container.</span></span> <span data-ttu-id="13d23-109">このプロパティの値: 1。</span><span class="sxs-lookup"><span data-stu-id="13d23-109">The value of this property for: 1.</span></span> <span data-ttu-id="13d23-110">Azure VM が Microsoft.Compute/virtualMachines 2 を計算します。</span><span class="sxs-lookup"><span data-stu-id="13d23-110">Compute Azure VM is Microsoft.Compute/virtualMachines 2.</span></span> <span data-ttu-id="13d23-111">クラシック Azure 仮想マシンのコンピューティングとは、Microsoft.ClassicCompute/virtualMachines 3 です。</span><span class="sxs-lookup"><span data-stu-id="13d23-111">Classic Compute Azure VM is Microsoft.ClassicCompute/virtualMachines 3.</span></span> <span data-ttu-id="13d23-112">(MAB、DPM など) のように Windows コンピューターとは、Windows 4 です。</span><span class="sxs-lookup"><span data-stu-id="13d23-112">Windows machines (like MAB, DPM etc) is Windows 4.</span></span> <span data-ttu-id="13d23-113">Azure の SQL インスタンスは、AzureSqlContainer です。</span><span class="sxs-lookup"><span data-stu-id="13d23-113">Azure SQL instance is AzureSqlContainer.</span></span> <span data-ttu-id="13d23-114">使用可能な値が含まれます: '無効'、'Unknown'、'IaasVMContainer'、'IaasVMServiceContainer'、'DPMContainer'、'AzureBackupServerContainer'、'MABContainer'、'をクラスター'、'AzureSqlContainer'、'Windows'、'VCenter'</span><span class="sxs-lookup"><span data-stu-id="13d23-114">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span></param>
        <summary>
            <span data-ttu-id="13d23-115">AzureSqlContainer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="13d23-115">Initializes a new instance of the AzureSqlContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>