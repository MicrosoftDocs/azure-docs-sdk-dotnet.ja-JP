<Type Name="BackupResourceVaultConfig" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig">
  <TypeSignature Language="C#" Value="public class BackupResourceVaultConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupResourceVaultConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupResourceVaultConfig" />
  <TypeSignature Language="F#" Value="type BackupResourceVaultConfig = class" />
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
            <span data-ttu-id="dc1bb-101">バックアップ リソース資格情報コンテナーの構成に関する詳細。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-101">Backup resource vault config details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupResourceVaultConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc1bb-102">BackupResourceVaultConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-102">Initializes a new instance of the BackupResourceVaultConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupResourceVaultConfig (string storageType = null, string storageTypeState = null, string enhancedSecurityState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageType, string storageTypeState, string enhancedSecurityState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageType As String = null, Optional storageTypeState As String = null, Optional enhancedSecurityState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig : string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig (storageType, storageTypeState, enhancedSecurityState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageType" Type="System.String" />
        <Parameter Name="storageTypeState" Type="System.String" />
        <Parameter Name="enhancedSecurityState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageType"><span data-ttu-id="dc1bb-103">記憶域の種類。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-103">Storage type.</span></span> <span data-ttu-id="dc1bb-104">使用可能な値が含まれます: '無効'、'GeoRedundant'、'LocallyRedundant'</span><span class="sxs-lookup"><span data-stu-id="dc1bb-104">Possible values include: 'Invalid', 'GeoRedundant', 'LocallyRedundant'</span></span></param>
        <param name="storageTypeState"><span data-ttu-id="dc1bb-105">ロックまたはロック解除します。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-105">Locked or Unlocked.</span></span> <span data-ttu-id="dc1bb-106">リソースに対して、コンピューターを登録すると、storageTypeState は常にロックされています。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-106">Once a machine is registered against a resource, the storageTypeState is always Locked.</span></span> <span data-ttu-id="dc1bb-107">使用可能な値が含まれます: '無効'、'ロック'、'ロックされていない'</span><span class="sxs-lookup"><span data-stu-id="dc1bb-107">Possible values include: 'Invalid', 'Locked', 'Unlocked'</span></span></param>
        <param name="enhancedSecurityState"><span data-ttu-id="dc1bb-108">有効または無効にします。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-108">Enabled or Disabled.</span></span> <span data-ttu-id="dc1bb-109">使用可能な値が含まれます: '無効'、'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="dc1bb-109">Possible values include: 'Invalid', 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="dc1bb-110">BackupResourceVaultConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-110">Initializes a new instance of the BackupResourceVaultConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnhancedSecurityState">
      <MemberSignature Language="C#" Value="public string EnhancedSecurityState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnhancedSecurityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.EnhancedSecurityState" />
      <MemberSignature Language="VB.NET" Value="Public Property EnhancedSecurityState As String" />
      <MemberSignature Language="F#" Value="member this.EnhancedSecurityState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.EnhancedSecurityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enhancedSecurityState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc1bb-111">取得または、有効または無効に設定します。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-111">Gets or sets enabled or Disabled.</span></span> <span data-ttu-id="dc1bb-112">使用可能な値が含まれます: '無効'、'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="dc1bb-112">Possible values include: 'Invalid', 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageType">
      <MemberSignature Language="C#" Value="public string StorageType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.StorageType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageType As String" />
      <MemberSignature Language="F#" Value="member this.StorageType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.StorageType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc1bb-113">取得または記憶域の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-113">Gets or sets storage type.</span></span> <span data-ttu-id="dc1bb-114">使用可能な値が含まれます: '無効'、'GeoRedundant'、'LocallyRedundant'</span><span class="sxs-lookup"><span data-stu-id="dc1bb-114">Possible values include: 'Invalid', 'GeoRedundant', 'LocallyRedundant'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageTypeState">
      <MemberSignature Language="C#" Value="public string StorageTypeState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageTypeState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.StorageTypeState" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageTypeState As String" />
      <MemberSignature Language="F#" Value="member this.StorageTypeState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig.StorageTypeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageTypeState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc1bb-115">取得またはロックまたはロック解除を設定します。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-115">Gets or sets locked or Unlocked.</span></span> <span data-ttu-id="dc1bb-116">リソースに対して、コンピューターを登録すると、storageTypeState は常にロックされています。</span><span class="sxs-lookup"><span data-stu-id="dc1bb-116">Once a machine is registered against a resource, the storageTypeState is always Locked.</span></span> <span data-ttu-id="dc1bb-117">使用可能な値が含まれます: '無効'、'ロック'、'ロックされていない'</span><span class="sxs-lookup"><span data-stu-id="dc1bb-117">Possible values include: 'Invalid', 'Locked', 'Unlocked'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>