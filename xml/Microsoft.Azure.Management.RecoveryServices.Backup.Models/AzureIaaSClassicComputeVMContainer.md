<Type Name="AzureIaaSClassicComputeVMContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer">
  <TypeSignature Language="C#" Value="public class AzureIaaSClassicComputeVMContainer : Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSClassicComputeVMContainer extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSClassicComputeVMContainer&#xA;Inherits IaaSVMContainer" />
  <TypeSignature Language="F#" Value="type AzureIaaSClassicComputeVMContainer = class&#xA;    inherit IaaSVMContainer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.ClassicCompute/virtualMachines")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="311bd-101">IaaS VM ワークロード固有バックアップを表す項目を従来の仮想マシン。</span><span class="sxs-lookup"><span data-stu-id="311bd-101">IaaS VM workload-specific backup item representing a classic virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSClassicComputeVMContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="311bd-102">AzureIaaSClassicComputeVMContainer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="311bd-102">Initializes a new instance of the AzureIaaSClassicComputeVMContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSClassicComputeVMContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null, string virtualMachineId = null, string virtualMachineVersion = null, string resourceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType, string virtualMachineId, string virtualMachineVersion, string resourceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null, Optional virtualMachineId As String = null, Optional virtualMachineVersion As String = null, Optional resourceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType, virtualMachineId, virtualMachineVersion, resourceGroup)" />
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
        <Parameter Name="virtualMachineId" Type="System.String" />
        <Parameter Name="virtualMachineVersion" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="friendlyName"><span data-ttu-id="311bd-103">コンテナーのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="311bd-103">Friendly name of the container.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="311bd-104">コンテナーのバックアップ managemenent の型。</span><span class="sxs-lookup"><span data-stu-id="311bd-104">Type of backup managemenent for the container.</span></span> <span data-ttu-id="311bd-105">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="311bd-105">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="311bd-106">Recovery Services コンテナーのコンテナーの登録の状態です。</span><span class="sxs-lookup"><span data-stu-id="311bd-106">Status of registration of the container with the Recovery Services Vault.</span></span></param>
        <param name="healthStatus"><span data-ttu-id="311bd-107">コンテナーの正常性の状態です。</span><span class="sxs-lookup"><span data-stu-id="311bd-107">Status of health of the container.</span></span></param>
        <param name="containerType"><span data-ttu-id="311bd-108">コンテナーの型。</span><span class="sxs-lookup"><span data-stu-id="311bd-108">Type of the container.</span></span> <span data-ttu-id="311bd-109">このプロパティの値: 1。</span><span class="sxs-lookup"><span data-stu-id="311bd-109">The value of this property for: 1.</span></span> <span data-ttu-id="311bd-110">Azure VM が Microsoft.Compute/virtualMachines 2 を計算します。</span><span class="sxs-lookup"><span data-stu-id="311bd-110">Compute Azure VM is Microsoft.Compute/virtualMachines 2.</span></span> <span data-ttu-id="311bd-111">クラシック Azure 仮想マシンのコンピューティングとは、Microsoft.ClassicCompute/virtualMachines 3 です。</span><span class="sxs-lookup"><span data-stu-id="311bd-111">Classic Compute Azure VM is Microsoft.ClassicCompute/virtualMachines 3.</span></span> <span data-ttu-id="311bd-112">(MAB、DPM など) のように Windows コンピューターとは、Windows 4 です。</span><span class="sxs-lookup"><span data-stu-id="311bd-112">Windows machines (like MAB, DPM etc) is Windows 4.</span></span> <span data-ttu-id="311bd-113">Azure の SQL インスタンスは、AzureSqlContainer です。</span><span class="sxs-lookup"><span data-stu-id="311bd-113">Azure SQL instance is AzureSqlContainer.</span></span> <span data-ttu-id="311bd-114">使用可能な値が含まれます: '無効'、'Unknown'、'IaasVMContainer'、'IaasVMServiceContainer'、'DPMContainer'、'AzureBackupServerContainer'、'MABContainer'、'をクラスター'、'AzureSqlContainer'、'Windows'、'VCenter'</span><span class="sxs-lookup"><span data-stu-id="311bd-114">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span></param>
        <param name="virtualMachineId"><span data-ttu-id="311bd-115">この Azure IaaS VM コンテナーによって表されるバーチャル マシンの ARM url の完全修飾します。</span><span class="sxs-lookup"><span data-stu-id="311bd-115">Fully qualified ARM url of the virtual machine represented by this Azure IaaS VM container.</span></span></param>
        <param name="virtualMachineVersion"><span data-ttu-id="311bd-116">コンテナーが、従来型または Azure リソース マネージャーの仮想マシンを表すかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="311bd-116">Specifies whether the container represents a Classic or an Azure Resource Manager VM.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="311bd-117">Recovery Services コンテナーのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="311bd-117">Resource group name of Recovery Services Vault.</span></span></param>
        <summary>
            <span data-ttu-id="311bd-118">AzureIaaSClassicComputeVMContainer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="311bd-118">Initializes a new instance of the AzureIaaSClassicComputeVMContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>