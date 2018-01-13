<Type Name="DpmJob" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob">
  <TypeSignature Language="C#" Value="public class DpmJob : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DpmJob extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob" />
  <TypeSignature Language="VB.NET" Value="Public Class DpmJob&#xA;Inherits Job" />
  <TypeSignature Language="F#" Value="type DpmJob = class&#xA;    inherit Job" />
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
            DPM ワークロード固有のジョブ オブジェクトです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DpmJob クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmJob (string entityFriendlyName = null, string backupManagementType = null, string operation = null, string status = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string activityId = null, Nullable&lt;TimeSpan&gt; duration = null, string dpmServerName = null, string containerName = null, string containerType = null, string workloadType = null, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; actionsInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo&gt; errorDetails = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityFriendlyName, string backupManagementType, string operation, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string activityId, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duration, string dpmServerName, string containerName, string containerType, string workloadType, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; actionsInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo&gt; errorDetails, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.TimeSpan},System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction}},System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo},Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional entityFriendlyName As String = null, Optional backupManagementType As String = null, Optional operation As String = null, Optional status As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional activityId As String = null, Optional duration As Nullable(Of TimeSpan) = null, Optional dpmServerName As String = null, Optional containerName As String = null, Optional containerType As String = null, Optional workloadType As String = null, Optional actionsInfo As IList(Of Nullable(Of JobSupportedAction)) = null, Optional errorDetails As IList(Of DpmErrorInfo) = null, Optional extendedInfo As DpmJobExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob : string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;TimeSpan&gt; * string * string * string * string * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob (entityFriendlyName, backupManagementType, operation, status, startTime, endTime, activityId, duration, dpmServerName, containerName, containerType, workloadType, actionsInfo, errorDetails, extendedInfo)" />
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
        <Parameter Name="dpmServerName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="containerType" Type="System.String" />
        <Parameter Name="workloadType" Type="System.String" />
        <Parameter Name="actionsInfo" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt;" />
        <Parameter Name="errorDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo&gt;" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="entityFriendlyName">現在のジョブが実行されているエンティティのフレンドリ名。</param>
        <param name="backupManagementType">現在のジョブを実行するバックアップ管理の種類。 使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</param>
        <param name="operation">操作の名前です。</param>
        <param name="status">ジョブの状態。</param>
        <param name="startTime">開始時刻です。</param>
        <param name="endTime">終了時刻。</param>
        <param name="activityId">ジョブの ActivityId です。</param>
        <param name="duration">ジョブの経過時間です。</param>
        <param name="dpmServerName">DPM サーバーの名前は、バックアップ項目またはバックアップ ジョブを管理します。</param>
        <param name="containerName">存在する場合は、現在のバックアップ項目を保護するクラスター/サーバーの名前です。</param>
        <param name="containerType">コンテナーの型。</param>
        <param name="workloadType">バックアップ項目の種類です。</param>
        <param name="actionsInfo">このジョブに適用可能な状態とアクションは、[キャンセル]/[再試行] をなどです。</param>
        <param name="errorDetails">エラーです。</param>
        <param name="extendedInfo">このジョブの追加情報です。</param>
        <summary>
            DpmJob クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionsInfo">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; ActionsInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; ActionsInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.ActionsInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionsInfo As IList(Of Nullable(Of JobSupportedAction))" />
      <MemberSignature Language="F#" Value="member this.ActionsInfo : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.ActionsInfo" />
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
            取得またはキャンセル/再試行と同様に、このジョブに適用可能な状態/アクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerName">
      <MemberSignature Language="C#" Value="public string ContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.ContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.ContainerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または存在する場合に、現在のバックアップ項目を保護するクラスター/サーバーの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerType">
      <MemberSignature Language="C#" Value="public string ContainerType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.ContainerType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerType As String" />
      <MemberSignature Language="F#" Value="member this.ContainerType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.ContainerType" />
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
            取得またはコンテナーの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DpmServerName">
      <MemberSignature Language="C#" Value="public string DpmServerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DpmServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.DpmServerName" />
      <MemberSignature Language="VB.NET" Value="Public Property DpmServerName As String" />
      <MemberSignature Language="F#" Value="member this.DpmServerName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.DpmServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dpmServerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ項目またはバックアップ ジョブを管理する DPM サーバー名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Duration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.Duration" />
      <MemberSignature Language="VB.NET" Value="Public Property Duration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Duration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.Duration" />
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
            取得または設定のジョブの経過時間。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo&gt; ErrorDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo&gt; ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorDetails As IList(Of DpmErrorInfo)" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.ErrorDetails" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmErrorInfo&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As DpmJobExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.ExtendedInfo" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJobExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、このジョブの追加情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkloadType">
      <MemberSignature Language="C#" Value="public string WorkloadType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkloadType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.WorkloadType" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkloadType As String" />
      <MemberSignature Language="F#" Value="member this.WorkloadType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmJob.WorkloadType" />
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
            取得またはバックアップ項目の種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>