<Type Name="AzureIaaSVMJob" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob">
  <TypeSignature Language="C#" Value="public class AzureIaaSVMJob : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSVMJob extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSVMJob&#xA;Inherits Job" />
  <TypeSignature Language="F#" Value="type AzureIaaSVMJob = class&#xA;    inherit Job" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5c460-101">Azure IaaS VM ワークロード固有のジョブ オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="5c460-101">Azure IaaS VM workload-specifc job object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5c460-102">AzureIaaSVMJob クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5c460-102">Initializes a new instance of the AzureIaaSVMJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMJob (string entityFriendlyName = null, string backupManagementType = null, string operation = null, string status = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string activityId = null, Nullable&lt;TimeSpan&gt; duration = null, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; actionsInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; errorDetails = null, string virtualMachineVersion = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityFriendlyName, string backupManagementType, string operation, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string activityId, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duration, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; actionsInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; errorDetails, string virtualMachineVersion, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction}},System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional entityFriendlyName As String = null, Optional backupManagementType As String = null, Optional operation As String = null, Optional status As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional activityId As String = null, Optional duration As Nullable(Of TimeSpan) = null, Optional actionsInfo As IList(Of Nullable(Of JobSupportedAction)) = null, Optional errorDetails As IList(Of AzureIaaSVMErrorInfo) = null, Optional virtualMachineVersion As String = null, Optional extendedInfo As AzureIaaSVMJobExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob : string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob (entityFriendlyName, backupManagementType, operation, status, startTime, endTime, activityId, duration, actionsInfo, errorDetails, virtualMachineVersion, extendedInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityFriendlyName" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="activityId" Type="System.String" />
        <Parameter Name="duration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="actionsInfo" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt;" />
        <Parameter Name="errorDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt;" />
        <Parameter Name="virtualMachineVersion" Type="System.String" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="entityFriendlyName"><span data-ttu-id="5c460-103">現在のジョブが実行されているエンティティのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="5c460-103">Friendly name of the entity on which the current job is executing.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="5c460-104">現在のジョブを実行するバックアップ管理の種類。</span><span class="sxs-lookup"><span data-stu-id="5c460-104">Backup management type to execute the current job.</span></span> <span data-ttu-id="5c460-105">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="5c460-105">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="operation"><span data-ttu-id="5c460-106">操作の名前です。</span><span class="sxs-lookup"><span data-stu-id="5c460-106">The operation name.</span></span></param>
        <param name="status"><span data-ttu-id="5c460-107">ジョブの状態。</span><span class="sxs-lookup"><span data-stu-id="5c460-107">Job status.</span></span></param>
        <param name="startTime"><span data-ttu-id="5c460-108">開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="5c460-108">The start time.</span></span></param>
        <param name="endTime"><span data-ttu-id="5c460-109">終了時刻。</span><span class="sxs-lookup"><span data-stu-id="5c460-109">The end time.</span></span></param>
        <param name="activityId"><span data-ttu-id="5c460-110">ジョブの ActivityId です。</span><span class="sxs-lookup"><span data-stu-id="5c460-110">ActivityId of job.</span></span></param>
        <param name="duration"><span data-ttu-id="5c460-111">このジョブの実行中に経過時間です。</span><span class="sxs-lookup"><span data-stu-id="5c460-111">Time elapsed during the execution of this job.</span></span></param>
        <param name="actionsInfo"><span data-ttu-id="5c460-112">取得またはキャンセル/再試行と同様に、このジョブに適用可能な状態/アクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="5c460-112">Gets or sets the state/actions applicable on this job like cancel/retry.</span></span></param>
        <param name="errorDetails"><span data-ttu-id="5c460-113">このジョブの実行でエラーの詳細。</span><span class="sxs-lookup"><span data-stu-id="5c460-113">Error details on execution of this job.</span></span></param>
        <param name="virtualMachineVersion"><span data-ttu-id="5c460-114">バックアップ アイテムが、従来型または Azure リソース マネージャーの仮想マシンであるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="5c460-114">Specifies whether the backup item is a Classic or an Azure Resource Manager VM.</span></span></param>
        <param name="extendedInfo"><span data-ttu-id="5c460-115">このジョブの追加情報です。</span><span class="sxs-lookup"><span data-stu-id="5c460-115">Additional information for this job.</span></span></param>
        <summary>
            <span data-ttu-id="5c460-116">AzureIaaSVMJob クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5c460-116">Initializes a new instance of the AzureIaaSVMJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionsInfo">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; ActionsInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; ActionsInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ActionsInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionsInfo As IList(Of Nullable(Of JobSupportedAction))" />
      <MemberSignature Language="F#" Value="member this.ActionsInfo : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ActionsInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionsInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c460-117">取得またはキャンセル/再試行と同様に、このジョブに適用可能な状態/アクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="5c460-117">Gets or sets the state/actions applicable on this job like cancel/retry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Duration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.Duration" />
      <MemberSignature Language="VB.NET" Value="Public Property Duration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Duration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.Duration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="duration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c460-118">取得または設定、このジョブの実行中に経過した時間。</span><span class="sxs-lookup"><span data-stu-id="5c460-118">Gets or sets time elapsed during the execution of this job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; ErrorDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorDetails As IList(Of AzureIaaSVMErrorInfo)" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ErrorDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c460-119">取得または、このジョブの実行でエラーの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c460-119">Gets or sets error details on execution of this job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As AzureIaaSVMJobExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ExtendedInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extendedInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c460-120">取得または、このジョブの追加情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c460-120">Gets or sets additional information for this job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineVersion">
      <MemberSignature Language="C#" Value="public string VirtualMachineVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.VirtualMachineVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineVersion As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.VirtualMachineVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c460-121">取得または設定は、バックアップの項目が、従来型または Azure リソース マネージャーの仮想マシンかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="5c460-121">Gets or sets specifies whether the backup item is a Classic or an Azure Resource Manager VM.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>