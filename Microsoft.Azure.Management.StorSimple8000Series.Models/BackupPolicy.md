<Type Name="BackupPolicy" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy">
  <TypeSignature Language="C#" Value="public class BackupPolicy : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupPolicy extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupPolicy&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type BackupPolicy = class&#xA;    inherit BaseModel" />
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
            バックアップ ポリシー。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackupPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupPolicy (System.Collections.Generic.IList&lt;string&gt; volumeIds, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;DateTime&gt; nextBackupTime = null, Nullable&lt;DateTime&gt; lastBackupTime = null, Nullable&lt;long&gt; schedulesCount = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; scheduledBackupStatus = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; backupPolicyCreationType = null, string ssmHostName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; volumeIds, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextBackupTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastBackupTime, valuetype System.Nullable`1&lt;int64&gt; schedulesCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; scheduledBackupStatus, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; backupPolicyCreationType, string ssmHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.#ctor(System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (volumeIds As IList(Of String), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional nextBackupTime As Nullable(Of DateTime) = null, Optional lastBackupTime As Nullable(Of DateTime) = null, Optional schedulesCount As Nullable(Of Long) = null, Optional scheduledBackupStatus As Nullable(Of ScheduledBackupStatus) = null, Optional backupPolicyCreationType As Nullable(Of BackupPolicyCreationType) = null, Optional ssmHostName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy : System.Collections.Generic.IList&lt;string&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy (volumeIds, id, name, type, kind, nextBackupTime, lastBackupTime, schedulesCount, scheduledBackupStatus, backupPolicyCreationType, ssmHostName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="volumeIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="nextBackupTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastBackupTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="schedulesCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="scheduledBackupStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt;" />
        <Parameter Name="backupPolicyCreationType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt;" />
        <Parameter Name="ssmHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="volumeIds">パス、バックアップ ポリシーに含まれるボリュームの Id です。</param>
        <param name="id">オブジェクトを一意に識別するパス ID です。</param>
        <param name="name">オブジェクトの名前。</param>
        <param name="type">オブジェクトの階層型です。</param>
        <param name="kind">オブジェクトの種類。 現在は Series8000 はサポートされています。 使用可能な値が含まれます: 'Series8000'</param>
        <param name="nextBackupTime">バックアップ ポリシーの次回のバックアップの時刻。</param>
        <param name="lastBackupTime">バックアップ ポリシーの最後のバックアップの時刻。</param>
        <param name="schedulesCount">バックアップ ポリシーが含まれるスケジュールの数。</param>
        <param name="scheduledBackupStatus">少なくとも 1 つのバックアップ ポリシーのスケジュールがアクティブであるかどうかどうかを示します。 使用可能な値が含まれます: '無効'、'Enabled'</param>
        <param name="backupPolicyCreationType">バックアップ ポリシーの作成の種類。 SaaS または StorSimple Snapshot Manager をこの作成されたかどうかを示します。 使用可能な値が含まれます: 'BySaaS'、'BySSM'</param>
        <param name="ssmHostName">バックアップ ポリシーが StorSimple Snapshot Manager によって作成された場合、このフィールドは、StorSimple Snapshot Manager のホスト名を示します。</param>
        <summary>
            BackupPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyCreationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; BackupPolicyCreationType { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; BackupPolicyCreationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.BackupPolicyCreationType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyCreationType As Nullable(Of BackupPolicyCreationType)" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyCreationType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.BackupPolicyCreationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupPolicyCreationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicyCreationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バックアップ ポリシーの作成の種類を取得します。 SaaS または StorSimple Snapshot Manager をこの作成されたかどうかを示します。
            使用可能な値が含まれます: 'BySaaS'、'BySSM'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBackupTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastBackupTime { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastBackupTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.LastBackupTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBackupTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastBackupTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.LastBackupTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastBackupTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バックアップ ポリシーの最後のバックアップの時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextBackupTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextBackupTime { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextBackupTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.NextBackupTime" />
      <MemberSignature Language="VB.NET" Value="Public Property NextBackupTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextBackupTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.NextBackupTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nextBackupTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バックアップ ポリシーのバックアップの次の時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledBackupStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; ScheduledBackupStatus { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; ScheduledBackupStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.ScheduledBackupStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledBackupStatus As Nullable(Of ScheduledBackupStatus)" />
      <MemberSignature Language="F#" Value="member this.ScheduledBackupStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.ScheduledBackupStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scheduledBackupStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduledBackupStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、少なくとも 1 つのバックアップ ポリシーのスケジュールがアクティブであるかどうかを示します。 使用可能な値が含まれます: '無効'、'Enabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulesCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SchedulesCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SchedulesCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.SchedulesCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulesCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SchedulesCount : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.SchedulesCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schedulesCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バックアップ ポリシーが含まれるスケジュールの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SsmHostName">
      <MemberSignature Language="C#" Value="public string SsmHostName { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SsmHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.SsmHostName" />
      <MemberSignature Language="VB.NET" Value="Public Property SsmHostName As String" />
      <MemberSignature Language="F#" Value="member this.SsmHostName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.SsmHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ssmHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このフィールドは、StorSimple Snapshot Manager のホスト名を示すし、バックアップ ポリシーには、StorSimple Snapshot Manager によってが作成された場合を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupPolicy.Validate " />
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
    <Member MemberName="VolumeIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VolumeIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VolumeIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.VolumeIds" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VolumeIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy.VolumeIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパス、バックアップ ポリシーに含まれるボリュームの Id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>