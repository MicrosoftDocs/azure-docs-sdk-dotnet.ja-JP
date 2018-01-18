<Type Name="UpdateBackupPolicyConfig" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig">
  <TypeSignature Language="C#" Value="public class UpdateBackupPolicyConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpdateBackupPolicyConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class UpdateBackupPolicyConfig" />
  <TypeSignature Language="F#" Value="type UpdateBackupPolicyConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateBackupPolicyConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="636ab-101">UpdateBackupPolicyConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="636ab-101">Initializes a new instance of the UpdateBackupPolicyConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateBackupPolicyConfig (string name, Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress operationInProgress, bool isPolicyRenamed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress operationInProgress, bool isPolicyRenamed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.#ctor(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress,System.Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig : string * Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress * bool -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig (name, operationInProgress, isPolicyRenamed)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="operationInProgress" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress" />
        <Parameter Name="isPolicyRenamed" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="operationInProgress">To be added.</param>
        <param name="isPolicyRenamed">To be added.</param>
        <summary>
            <span data-ttu-id="636ab-102">必須の引数で UpdateBackupPolicyConfig クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="636ab-102">Initializes a new instance of the UpdateBackupPolicyConfig class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSchedulesToBeAdded">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase&gt; BackupSchedulesToBeAdded { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase&gt; BackupSchedulesToBeAdded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.BackupSchedulesToBeAdded" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSchedulesToBeAdded As IList(Of BackupScheduleBase)" />
      <MemberSignature Language="F#" Value="member this.BackupSchedulesToBeAdded : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.BackupSchedulesToBeAdded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleBase&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="636ab-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="636ab-103">Optional.</span></span> <span data-ttu-id="636ab-104">バックアップのスケジュールでは、バックアップ ポリシーに追加します。</span><span class="sxs-lookup"><span data-stu-id="636ab-104">The backup schedules added to the backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSchedulesToBeDeleted">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; BackupSchedulesToBeDeleted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; BackupSchedulesToBeDeleted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.BackupSchedulesToBeDeleted" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSchedulesToBeDeleted As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.BackupSchedulesToBeDeleted : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.BackupSchedulesToBeDeleted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="636ab-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="636ab-105">Optional.</span></span> <span data-ttu-id="636ab-106">バックアップのスケジュールでは、バックアップ ポリシーから削除します。</span><span class="sxs-lookup"><span data-stu-id="636ab-106">The backup schedules deleted from the backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSchedulesToBeUpdated">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleUpdateRequest&gt; BackupSchedulesToBeUpdated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleUpdateRequest&gt; BackupSchedulesToBeUpdated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.BackupSchedulesToBeUpdated" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSchedulesToBeUpdated As IList(Of BackupScheduleUpdateRequest)" />
      <MemberSignature Language="F#" Value="member this.BackupSchedulesToBeUpdated : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleUpdateRequest&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.BackupSchedulesToBeUpdated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleUpdateRequest&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="636ab-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="636ab-107">Optional.</span></span> <span data-ttu-id="636ab-108">バックアップのスケジュールでは、バックアップ ポリシーで更新します。</span><span class="sxs-lookup"><span data-stu-id="636ab-108">The backup schedules updated in the backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="636ab-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="636ab-109">Optional.</span></span> <span data-ttu-id="636ab-110">インスタンス識別子</span><span class="sxs-lookup"><span data-stu-id="636ab-110">The instance identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPolicyRenamed">
      <MemberSignature Language="C#" Value="public bool IsPolicyRenamed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPolicyRenamed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.IsPolicyRenamed" />
      <MemberSignature Language="VB.NET" Value="Public Property IsPolicyRenamed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPolicyRenamed : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.IsPolicyRenamed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="636ab-111">必須。</span><span class="sxs-lookup"><span data-stu-id="636ab-111">Required.</span></span> <span data-ttu-id="636ab-112">ポリシーの名前が変更されます。</span><span class="sxs-lookup"><span data-stu-id="636ab-112">Is the policy renamed</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="636ab-113">必須。</span><span class="sxs-lookup"><span data-stu-id="636ab-113">Required.</span></span> <span data-ttu-id="636ab-114">エンティティの名前</span><span class="sxs-lookup"><span data-stu-id="636ab-114">The name of the entity</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationInProgress">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress OperationInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress OperationInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.OperationInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationInProgress As OperationInProgress" />
      <MemberSignature Language="F#" Value="member this.OperationInProgress : Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.OperationInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="636ab-115">必須。</span><span class="sxs-lookup"><span data-stu-id="636ab-115">Required.</span></span> <span data-ttu-id="636ab-116">操作が進行中</span><span class="sxs-lookup"><span data-stu-id="636ab-116">Operation In Progress</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VolumeIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VolumeIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.VolumeIds" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VolumeIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig.VolumeIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="636ab-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="636ab-117">Optional.</span></span> <span data-ttu-id="636ab-118">このバックアップ ポリシー下にあるボリューム id の一覧。</span><span class="sxs-lookup"><span data-stu-id="636ab-118">The list of volume ids under this backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>