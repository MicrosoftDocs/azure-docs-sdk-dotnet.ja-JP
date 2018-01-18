<Type Name="BackupVaultConfig" FullName="Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig">
  <TypeSignature Language="C#" Value="public class BackupVaultConfig : Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupVaultConfig extends Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupVaultConfig&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BackupVaultConfig = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="36f6b-101">バックアップ コンテナーの構成に関する詳細。</span><span class="sxs-lookup"><span data-stu-id="36f6b-101">Backup vault config details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="36f6b-102">BackupVaultConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="36f6b-102">Initializes a new instance of the BackupVaultConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultConfig (string id = null, string name = null, string type = null, string eTag = null, string storageType = null, string storageTypeState = null, string enhancedSecurityState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string eTag, string storageType, string storageTypeState, string enhancedSecurityState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional eTag As String = null, Optional storageType As String = null, Optional storageTypeState As String = null, Optional enhancedSecurityState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig (id, name, type, eTag, storageType, storageTypeState, enhancedSecurityState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="storageType" Type="System.String" />
        <Parameter Name="storageTypeState" Type="System.String" />
        <Parameter Name="enhancedSecurityState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="36f6b-103">リソース Id は、リソースへの完全なパスを表します。</span><span class="sxs-lookup"><span data-stu-id="36f6b-103">Resource Id represents the complete path to the resource.</span></span></param>
        <param name="name"><span data-ttu-id="36f6b-104">リソースに関連付けられているリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="36f6b-104">Resource name associated with the resource.</span></span></param>
        <param name="type"><span data-ttu-id="36f6b-105">リソースの種類は Namespace/ResourceType/ResourceType/... 形式の完全なパスを表します</span><span class="sxs-lookup"><span data-stu-id="36f6b-105">Resource type represents the complete path of the form Namespace/ResourceType/ResourceType/...</span></span></param>
        <param name="eTag"><span data-ttu-id="36f6b-106">省略可能な ETag です。</span><span class="sxs-lookup"><span data-stu-id="36f6b-106">Optional ETag.</span></span></param>
        <param name="storageType"><span data-ttu-id="36f6b-107">記憶域の種類。</span><span class="sxs-lookup"><span data-stu-id="36f6b-107">Storage type.</span></span> <span data-ttu-id="36f6b-108">使用可能な値が含まれます: '無効'、'GeoRedundant'、'LocallyRedundant'</span><span class="sxs-lookup"><span data-stu-id="36f6b-108">Possible values include: 'Invalid', 'GeoRedundant', 'LocallyRedundant'</span></span></param>
        <param name="storageTypeState"><span data-ttu-id="36f6b-109">ロックまたはロック解除します。</span><span class="sxs-lookup"><span data-stu-id="36f6b-109">Locked or Unlocked.</span></span> <span data-ttu-id="36f6b-110">リソースに対して、コンピューターを登録すると、storageTypeState は常にロックされています。</span><span class="sxs-lookup"><span data-stu-id="36f6b-110">Once a machine is registered against a resource, the storageTypeState is always Locked.</span></span> <span data-ttu-id="36f6b-111">使用可能な値が含まれます: '無効'、'ロック'、'ロックされていない'</span><span class="sxs-lookup"><span data-stu-id="36f6b-111">Possible values include: 'Invalid', 'Locked', 'Unlocked'</span></span></param>
        <param name="enhancedSecurityState"><span data-ttu-id="36f6b-112">有効または無効にします。</span><span class="sxs-lookup"><span data-stu-id="36f6b-112">Enabled or Disabled.</span></span> <span data-ttu-id="36f6b-113">使用可能な値が含まれます: '無効'、'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="36f6b-113">Possible values include: 'Invalid', 'Enabled', 'Disabled'</span></span></param>
        <summary>
            <span data-ttu-id="36f6b-114">BackupVaultConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="36f6b-114">Initializes a new instance of the BackupVaultConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnhancedSecurityState">
      <MemberSignature Language="C#" Value="public string EnhancedSecurityState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnhancedSecurityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.EnhancedSecurityState" />
      <MemberSignature Language="VB.NET" Value="Public Property EnhancedSecurityState As String" />
      <MemberSignature Language="F#" Value="member this.EnhancedSecurityState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.EnhancedSecurityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enhancedSecurityState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36f6b-115">取得または、有効または無効に設定します。</span><span class="sxs-lookup"><span data-stu-id="36f6b-115">Gets or sets enabled or Disabled.</span></span> <span data-ttu-id="36f6b-116">使用可能な値が含まれます: '無効'、'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="36f6b-116">Possible values include: 'Invalid', 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageType">
      <MemberSignature Language="C#" Value="public string StorageType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.StorageType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageType As String" />
      <MemberSignature Language="F#" Value="member this.StorageType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.StorageType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36f6b-117">取得または記憶域の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="36f6b-117">Gets or sets storage type.</span></span> <span data-ttu-id="36f6b-118">使用可能な値が含まれます: '無効'、'GeoRedundant'、'LocallyRedundant'</span><span class="sxs-lookup"><span data-stu-id="36f6b-118">Possible values include: 'Invalid', 'GeoRedundant', 'LocallyRedundant'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageTypeState">
      <MemberSignature Language="C#" Value="public string StorageTypeState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageTypeState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.StorageTypeState" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageTypeState As String" />
      <MemberSignature Language="F#" Value="member this.StorageTypeState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupVaultConfig.StorageTypeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageTypeState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36f6b-119">取得またはロックまたはロック解除を設定します。</span><span class="sxs-lookup"><span data-stu-id="36f6b-119">Gets or sets locked or Unlocked.</span></span> <span data-ttu-id="36f6b-120">リソースに対して、コンピューターを登録すると、storageTypeState は常にロックされています。</span><span class="sxs-lookup"><span data-stu-id="36f6b-120">Once a machine is registered against a resource, the storageTypeState is always Locked.</span></span> <span data-ttu-id="36f6b-121">使用可能な値が含まれます: '無効'、'ロック'、'ロックされていない'</span><span class="sxs-lookup"><span data-stu-id="36f6b-121">Possible values include: 'Invalid', 'Locked', 'Unlocked'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>