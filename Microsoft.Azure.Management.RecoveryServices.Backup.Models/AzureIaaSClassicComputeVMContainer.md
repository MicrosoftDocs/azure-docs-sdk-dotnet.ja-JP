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
            IaaS VM ワークロード固有バックアップを表す項目を従来の仮想マシン。
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
            AzureIaaSClassicComputeVMContainer クラスの新しいインスタンスを初期化します。
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
        <param name="friendlyName">コンテナーのフレンドリ名。</param>
        <param name="backupManagementType">コンテナーのバックアップ managemenent の型。 使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</param>
        <param name="registrationStatus">Recovery Services コンテナーのコンテナーの登録の状態です。</param>
        <param name="healthStatus">コンテナーの正常性の状態です。</param>
        <param name="containerType">コンテナーの型。 このプロパティの値: 1。 Azure VM が Microsoft.Compute/virtualMachines 2 を計算します。 クラシック Azure 仮想マシンのコンピューティングとは、Microsoft.ClassicCompute/virtualMachines 3 です。 (MAB、DPM など) のように Windows コンピューターとは、Windows 4 です。 Azure の SQL インスタンスは、AzureSqlContainer です。 使用可能な値が含まれます: '無効'、'Unknown'、'IaasVMContainer'、'IaasVMServiceContainer'、'DPMContainer'、'AzureBackupServerContainer'、'MABContainer'、'をクラスター'、'AzureSqlContainer'、'Windows'、'VCenter'</param>
        <param name="virtualMachineId">この Azure IaaS VM コンテナーによって表されるバーチャル マシンの ARM url の完全修飾します。</param>
        <param name="virtualMachineVersion">コンテナーが、従来型または Azure リソース マネージャーの仮想マシンを表すかどうかを指定します。</param>
        <param name="resourceGroup">Recovery Services コンテナーのリソース グループ名。</param>
        <summary>
            AzureIaaSClassicComputeVMContainer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>