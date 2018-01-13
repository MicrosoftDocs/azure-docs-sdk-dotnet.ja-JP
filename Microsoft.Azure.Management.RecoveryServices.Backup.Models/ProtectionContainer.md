<Type Name="ProtectionContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer">
  <TypeSignature Language="C#" Value="public class ProtectionContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProtectionContainer extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class ProtectionContainer" />
  <TypeSignature Language="F#" Value="type ProtectionContainer = class" />
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
            バックアップ アイテムのコンテナーの基本クラス。 特定のワークロードを使用したコンテナーは、このクラスから派生します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ProtectionContainer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer : string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType)" />
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
        <param name="friendlyName">コンテナーのフレンドリ名。</param>
        <param name="backupManagementType">コンテナーのバックアップ managemenent の型。 使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</param>
        <param name="registrationStatus">Recovery Services コンテナーのコンテナーの登録の状態です。</param>
        <param name="healthStatus">コンテナーの正常性の状態です。</param>
        <param name="containerType">コンテナーの型。 このプロパティの値: 1。 Azure VM が Microsoft.Compute/virtualMachines 2 を計算します。 クラシック Azure 仮想マシンのコンピューティングとは、Microsoft.ClassicCompute/virtualMachines 3 です。 (MAB、DPM など) のように Windows コンピューターとは、Windows 4 です。 Azure の SQL インスタンスは、AzureSqlContainer です。 使用可能な値が含まれます: '無効'、'Unknown'、'IaasVMContainer'、'IaasVMServiceContainer'、'DPMContainer'、'AzureBackupServerContainer'、'MABContainer'、'をクラスター'、'AzureSqlContainer'、'Windows'、'VCenter'</param>
        <summary>
            ProtectionContainer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.BackupManagementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupManagementType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナーのバックアップ managemenent の種類を設定します。
            使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerType">
      <MemberSignature Language="C#" Value="public string ContainerType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.ContainerType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerType As String" />
      <MemberSignature Language="F#" Value="member this.ContainerType : string" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.ContainerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンテナーの型を取得します。 このプロパティの値: 1。
            Azure VM が Microsoft.Compute/virtualMachines 2 を計算します。 クラシック Azure 仮想マシンのコンピューティングとは、Microsoft.ClassicCompute/virtualMachines 3 です。
            (MAB、DPM など) のように Windows コンピューターとは、Windows 4 です。 Azure の SQL インスタンスは、AzureSqlContainer です。 使用可能な値が含まれます: '無効'、'Unknown'、'IaasVMContainer'、'IaasVMServiceContainer'、'DPMContainer'、'AzureBackupServerContainer'、'MABContainer'、'をクラスター'、'AzureSqlContainer'、'Windows'、'VCenter'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナーのフレンドリ名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatus">
      <MemberSignature Language="C#" Value="public string HealthStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HealthStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.HealthStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatus As String" />
      <MemberSignature Language="F#" Value="member this.HealthStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.HealthStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンテナーの正常性の状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationStatus">
      <MemberSignature Language="C#" Value="public string RegistrationStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.RegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistrationStatus As String" />
      <MemberSignature Language="F#" Value="member this.RegistrationStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.RegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="registrationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Recovery Services コンテナーのコンテナーの登録の状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>