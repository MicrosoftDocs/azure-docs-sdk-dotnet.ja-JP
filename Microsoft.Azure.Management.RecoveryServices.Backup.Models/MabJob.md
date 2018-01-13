<Type Name="MabJob" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob">
  <TypeSignature Language="C#" Value="public class MabJob : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MabJob extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob" />
  <TypeSignature Language="VB.NET" Value="Public Class MabJob&#xA;Inherits Job" />
  <TypeSignature Language="F#" Value="type MabJob = class&#xA;    inherit Job" />
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
            MAB ワークロードに固有のジョブです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            MabJob クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabJob (string entityFriendlyName = null, string backupManagementType = null, string operation = null, string status = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string activityId = null, Nullable&lt;TimeSpan&gt; duration = null, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; actionsInfo = null, string mabServerName = null, string mabServerType = null, string workloadType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo&gt; errorDetails = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJobExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityFriendlyName, string backupManagementType, string operation, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string activityId, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duration, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; actionsInfo, string mabServerName, string mabServerType, string workloadType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo&gt; errorDetails, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJobExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction}},System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo},Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJobExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional entityFriendlyName As String = null, Optional backupManagementType As String = null, Optional operation As String = null, Optional status As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional activityId As String = null, Optional duration As Nullable(Of TimeSpan) = null, Optional actionsInfo As IList(Of Nullable(Of JobSupportedAction)) = null, Optional mabServerName As String = null, Optional mabServerType As String = null, Optional workloadType As String = null, Optional errorDetails As IList(Of MabErrorInfo) = null, Optional extendedInfo As MabJobExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob : string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJobExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob (entityFriendlyName, backupManagementType, operation, status, startTime, endTime, activityId, duration, actionsInfo, mabServerName, mabServerType, workloadType, errorDetails, extendedInfo)" />
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
        <Parameter Name="mabServerName" Type="System.String" />
        <Parameter Name="mabServerType" Type="System.String" />
        <Parameter Name="workloadType" Type="System.String" />
        <Parameter Name="errorDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo&gt;" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJobExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="entityFriendlyName">現在のジョブが実行されているエンティティのフレンドリ名。</param>
        <param name="backupManagementType">現在のジョブを実行するバックアップ管理の種類。 使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</param>
        <param name="operation">操作の名前です。</param>
        <param name="status">ジョブの状態。</param>
        <param name="startTime">開始時刻です。</param>
        <param name="endTime">終了時刻。</param>
        <param name="activityId">ジョブの ActivityId です。</param>
        <param name="duration">ジョブが実行に要した時間。</param>
        <param name="actionsInfo">ジョブに適用可能な状態/アクションでは、[キャンセル]/[再試行] と同様にします。</param>
        <param name="mabServerName">DS を保護するサーバーの名前です。</param>
        <param name="mabServerType">MAB コンテナーのサーバーの種類。 使用可能な値が含まれます: '無効'、'Unknown'、'IaasVMContainer'、'IaasVMServiceContainer'、'DPMContainer'、'AzureBackupServerContainer'、'MABContainer'、'をクラスター'、'AzureSqlContainer'、'Windows'、'VCenter'</param>
        <param name="workloadType">バックアップ項目のワークロードの種類。 使用可能な値が含まれます: '無効'、'VM'、'ファイル フォルダー'、'AzureSqlDb'、'SQLDB'、'交換'、'Sharepoint'、'VMwareVM'、'SystemState'、'Client'、'GenericDataSource'</param>
        <param name="errorDetails">エラーです。</param>
        <param name="extendedInfo">ジョブの詳細についてはします。</param>
        <summary>
            MabJob クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionsInfo">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; ActionsInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; ActionsInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.ActionsInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionsInfo As IList(Of Nullable(Of JobSupportedAction))" />
      <MemberSignature Language="F#" Value="member this.ActionsInfo : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.ActionsInfo" />
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
            取得またはキャンセル/再試行などのジョブの状態/アクションを適用可能な設定です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Duration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.Duration" />
      <MemberSignature Language="VB.NET" Value="Public Property Duration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Duration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.Duration" />
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
            取得またはジョブが実行に要した時間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo&gt; ErrorDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo&gt; ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorDetails As IList(Of MabErrorInfo)" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.ErrorDetails" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabErrorInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定エラー。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJobExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJobExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As MabJobExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJobExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.ExtendedInfo" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJobExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または追加情報をジョブに設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MabServerName">
      <MemberSignature Language="C#" Value="public string MabServerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MabServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.MabServerName" />
      <MemberSignature Language="VB.NET" Value="Public Property MabServerName As String" />
      <MemberSignature Language="F#" Value="member this.MabServerName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.MabServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mabServerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または DS を保護するサーバーの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MabServerType">
      <MemberSignature Language="C#" Value="public string MabServerType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MabServerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.MabServerType" />
      <MemberSignature Language="VB.NET" Value="Public Property MabServerType As String" />
      <MemberSignature Language="F#" Value="member this.MabServerType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.MabServerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mabServerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または MAB コンテナーのサーバーの種類を設定します。 使用可能な値が含まれます: '無効'、'Unknown'、'IaasVMContainer'、'IaasVMServiceContainer'、'DPMContainer'、'AzureBackupServerContainer'、'MABContainer'、'をクラスター'、'AzureSqlContainer'、'Windows'、'VCenter'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkloadType">
      <MemberSignature Language="C#" Value="public string WorkloadType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkloadType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.WorkloadType" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkloadType As String" />
      <MemberSignature Language="F#" Value="member this.WorkloadType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabJob.WorkloadType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workloadType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ項目のワークロードの種類を設定します。 使用可能な値が含まれます: '無効'、'VM'、'ファイル フォルダー'、'AzureSqlDb'、'SQLDB'、'交換'、'Sharepoint'、'VMwareVM'、'SystemState'、'Client'、'GenericDataSource'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>