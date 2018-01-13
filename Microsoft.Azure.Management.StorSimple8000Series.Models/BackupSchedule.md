<Type Name="BackupSchedule" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule">
  <TypeSignature Language="C#" Value="public class BackupSchedule : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupSchedule extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupSchedule&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type BackupSchedule = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            バックアップのスケジュールです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackupSchedule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupSchedule (Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence scheduleRecurrence, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType backupType, long retentionCount, DateTime startTime, Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus scheduleStatus, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;DateTime&gt; lastSuccessfulRun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence scheduleRecurrence, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType backupType, int64 retentionCount, valuetype System.DateTime startTime, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus scheduleStatus, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastSuccessfulRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType,System.Int64,System.DateTime,Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.DateTime})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule : Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType * int64 * DateTime * Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule (scheduleRecurrence, backupType, retentionCount, startTime, scheduleStatus, id, name, type, kind, lastSuccessfulRun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scheduleRecurrence" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence" />
        <Parameter Name="backupType" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType" />
        <Parameter Name="retentionCount" Type="System.Int64" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="scheduleStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="lastSuccessfulRun" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="scheduleRecurrence">スケジュールの繰り返しです。</param>
        <param name="backupType">実行する必要があるバックアップの種類。 使用可能な値が含まれます: 'LocalSnapshot'、'CloudSnapshot'</param>
        <param name="retentionCount">保持されるバックアップの数。</param>
        <param name="startTime">スケジュールの開始時刻です。</param>
        <param name="scheduleStatus">スケジュールの状態。 使用可能な値が含まれます: 'Enabled'、'Disabled'</param>
        <param name="id">オブジェクトを一意に識別するパス ID です。</param>
        <param name="name">オブジェクトの名前。</param>
        <param name="type">オブジェクトの階層型です。</param>
        <param name="kind">オブジェクトの種類。 現在は Series8000 はサポートされています。 使用可能な値が含まれます: 'Series8000'</param>
        <param name="lastSuccessfulRun">最後のバックアップ スケジュールのトリガーされたを実行します。</param>
        <summary>
            BackupSchedule クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType BackupType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType BackupType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.BackupType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupType As BackupType" />
      <MemberSignature Language="F#" Value="member this.BackupType : Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.BackupType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または実行する必要があるバックアップの種類を設定します。 使用可能な値が含まれます: 'LocalSnapshot'、'CloudSnapshot'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSuccessfulRun">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastSuccessfulRun { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastSuccessfulRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.LastSuccessfulRun" />
      <MemberSignature Language="VB.NET" Value="Public Property LastSuccessfulRun As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastSuccessfulRun : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.LastSuccessfulRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastSuccessfulRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            実行のスケジュールがトリガーされた最後のバックアップを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionCount">
      <MemberSignature Language="C#" Value="public long RetentionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RetentionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.RetentionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionCount As Long" />
      <MemberSignature Language="F#" Value="member this.RetentionCount : int64 with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.RetentionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または保持されるバックアップの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleRecurrence">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence ScheduleRecurrence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence ScheduleRecurrence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleRecurrence" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleRecurrence As ScheduleRecurrence" />
      <MemberSignature Language="F#" Value="member this.ScheduleRecurrence : Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleRecurrence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scheduleRecurrence")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスケジュールの繰り返しを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus ScheduleStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus ScheduleStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleStatus As ScheduleStatus" />
      <MemberSignature Language="F#" Value="member this.ScheduleStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scheduleStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスケジュールの状態を設定します。 使用可能な値が含まれます: 'Enabled'、'Disabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスケジュールの開始時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupSchedule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>