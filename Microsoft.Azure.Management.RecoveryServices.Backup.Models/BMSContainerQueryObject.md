<Type Name="BMSContainerQueryObject" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject">
  <TypeSignature Language="C#" Value="public class BMSContainerQueryObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BMSContainerQueryObject extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject" />
  <TypeSignature Language="VB.NET" Value="Public Class BMSContainerQueryObject" />
  <TypeSignature Language="F#" Value="type BMSContainerQueryObject = class" />
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
            <span data-ttu-id="7356c-101">リスト コンテナー API で使用できるクエリのフィルター。</span><span class="sxs-lookup"><span data-stu-id="7356c-101">The query filters that can be used with the list containers API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BMSContainerQueryObject ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7356c-102">BMSContainerQueryObject クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7356c-102">Initializes a new instance of the BMSContainerQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BMSContainerQueryObject (string backupManagementType, string containerType = null, string backupEngineName = null, string status = null, string friendlyName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string containerType, string backupEngineName, string status, string friendlyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (backupManagementType As String, Optional containerType As String = null, Optional backupEngineName As String = null, Optional status As String = null, Optional friendlyName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject : string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject (backupManagementType, containerType, backupEngineName, status, friendlyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="containerType" Type="System.String" />
        <Parameter Name="backupEngineName" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="friendlyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupManagementType"><span data-ttu-id="7356c-103">このコンテナーのバックアップの管理の種類。</span><span class="sxs-lookup"><span data-stu-id="7356c-103">Backup management type for this container.</span></span> <span data-ttu-id="7356c-104">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="7356c-104">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="containerType"><span data-ttu-id="7356c-105">フィルターのコンテナーの型。</span><span class="sxs-lookup"><span data-stu-id="7356c-105">Type of container for filter.</span></span> <span data-ttu-id="7356c-106">使用可能な値が含まれます: '無効'、'Unknown'、'IaasVMContainer'、'IaasVMServiceContainer'、'DPMContainer'、'AzureBackupServerContainer'、'MABContainer'、'をクラスター'、'AzureSqlContainer'、'Windows'、'VCenter'</span><span class="sxs-lookup"><span data-stu-id="7356c-106">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span></param>
        <param name="backupEngineName"><span data-ttu-id="7356c-107">バックアップ エンジン名</span><span class="sxs-lookup"><span data-stu-id="7356c-107">Backup engine name</span></span></param>
        <param name="status"><span data-ttu-id="7356c-108">Recovery Services コンテナーでは、このコンテナーの登録の状態です。</span><span class="sxs-lookup"><span data-stu-id="7356c-108">Status of registration of this container with the Recovery Services Vault.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="7356c-109">このコンテナーのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="7356c-109">Friendly name of this container.</span></span></param>
        <summary>
            <span data-ttu-id="7356c-110">BMSContainerQueryObject クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7356c-110">Initializes a new instance of the BMSContainerQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupEngineName">
      <MemberSignature Language="C#" Value="public string BackupEngineName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupEngineName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.BackupEngineName" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupEngineName As String" />
      <MemberSignature Language="F#" Value="member this.BackupEngineName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.BackupEngineName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupEngineName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7356c-111">取得または設定のバックアップ エンジン名</span><span class="sxs-lookup"><span data-stu-id="7356c-111">Gets or sets backup engine name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.BackupManagementType" />
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
            <span data-ttu-id="7356c-112">取得または、このコンテナーのバックアップの管理の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="7356c-112">Gets or sets backup management type for this container.</span></span> <span data-ttu-id="7356c-113">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="7356c-113">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerType">
      <MemberSignature Language="C#" Value="public string ContainerType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.ContainerType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerType As String" />
      <MemberSignature Language="F#" Value="member this.ContainerType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.ContainerType" />
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
            <span data-ttu-id="7356c-114">取得またはフィルターのコンテナーの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="7356c-114">Gets or sets type of container for filter.</span></span> <span data-ttu-id="7356c-115">使用可能な値が含まれます: '無効'、'Unknown'、'IaasVMContainer'、'IaasVMServiceContainer'、'DPMContainer'、'AzureBackupServerContainer'、'MABContainer'、'をクラスター'、'AzureSqlContainer'、'Windows'、'VCenter'</span><span class="sxs-lookup"><span data-stu-id="7356c-115">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.FriendlyName" />
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
            <span data-ttu-id="7356c-116">取得または、このコンテナーのフレンドリ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="7356c-116">Gets or sets friendly name of this container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7356c-117">取得または Recovery Services コンテナーでは、このコンテナーの登録の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="7356c-117">Gets or sets status of registration of this container with the Recovery Services Vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSContainerQueryObject.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="bMSContainerQueryObject.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7356c-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7356c-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7356c-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7356c-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>