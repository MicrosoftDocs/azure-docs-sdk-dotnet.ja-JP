<Type Name="Backup" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup">
  <TypeSignature Language="C#" Value="public class Backup : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Backup extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup" />
  <TypeSignature Language="VB.NET" Value="Public Class Backup&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Backup = class&#xA;    inherit BaseModel" />
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
            バックアップします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Backup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            バックアップ クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Backup (DateTime createdOn, long sizeInBytes, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; elements, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; backupType = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; backupJobCreationType = null, string backupPolicyId = null, string ssmHostName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime createdOn, int64 sizeInBytes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; elements, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; backupType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; backupJobCreationType, string backupPolicyId, string ssmHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.#ctor(System.DateTime,System.Int64,System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createdOn As DateTime, sizeInBytes As Long, elements As IList(Of BackupElement), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional backupType As Nullable(Of BackupType) = null, Optional backupJobCreationType As Nullable(Of BackupJobCreationType) = null, Optional backupPolicyId As String = null, Optional ssmHostName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Backup : DateTime * int64 * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Backup" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Backup (createdOn, sizeInBytes, elements, id, name, type, kind, backupType, backupJobCreationType, backupPolicyId, ssmHostName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createdOn" Type="System.DateTime" />
        <Parameter Name="sizeInBytes" Type="System.Int64" />
        <Parameter Name="elements" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="backupType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt;" />
        <Parameter Name="backupJobCreationType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt;" />
        <Parameter Name="backupPolicyId" Type="System.String" />
        <Parameter Name="ssmHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="createdOn">バックアップが作成された時刻。</param>
        <param name="sizeInBytes">バックアップのサイズ (バイト単位)。</param>
        <param name="elements">バックアップ要素。</param>
        <param name="id">オブジェクトを一意に識別するパス ID です。</param>
        <param name="name">オブジェクトの名前。</param>
        <param name="type">オブジェクトの階層型です。</param>
        <param name="kind">オブジェクトの種類。 現在は Series8000 はサポートされています。 使用可能な値が含まれます: 'Series8000'</param>
        <param name="backupType">バックアップの種類。 使用可能な値が含まれます: 'LocalSnapshot'、'CloudSnapshot'</param>
        <param name="backupJobCreationType">バックアップ ジョブの作成の種類。
            使用可能な値が含まれます: 'アドホック'、'BySchedule'、'BySSM'</param>
        <param name="backupPolicyId">バックアップ ポリシーのパス ID。</param>
        <param name="ssmHostName">StorSimple Snapshot Manager のホスト名です。</param>
        <summary>
            バックアップ クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupJobCreationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; BackupJobCreationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; BackupJobCreationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupJobCreationType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupJobCreationType As Nullable(Of BackupJobCreationType)" />
      <MemberSignature Language="F#" Value="member this.BackupJobCreationType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupJobCreationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupJobCreationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ ジョブの作成の種類を設定します。 使用可能な値が含まれます: 'アドホック'、'BySchedule'、'BySSM'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyId">
      <MemberSignature Language="C#" Value="public string BackupPolicyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupPolicyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupPolicyId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyId As String" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupPolicyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupPolicyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ ポリシーのパス ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; BackupType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; BackupType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupType As Nullable(Of BackupType)" />
      <MemberSignature Language="F#" Value="member this.BackupType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupType" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップの種類を設定します。 使用可能な値が含まれます: 'LocalSnapshot'、'CloudSnapshot'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedOn">
      <MemberSignature Language="C#" Value="public DateTime CreatedOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.CreatedOn" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedOn As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedOn : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.CreatedOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdOn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップが作成された時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Elements">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; Elements { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; Elements" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.Elements" />
      <MemberSignature Language="VB.NET" Value="Public Property Elements As IList(Of BackupElement)" />
      <MemberSignature Language="F#" Value="member this.Elements : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.Elements" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.elements")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップの要素を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64 with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップのサイズをバイト単位で設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SsmHostName">
      <MemberSignature Language="C#" Value="public string SsmHostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SsmHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.SsmHostName" />
      <MemberSignature Language="VB.NET" Value="Public Property SsmHostName As String" />
      <MemberSignature Language="F#" Value="member this.SsmHostName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.SsmHostName" />
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
            取得または StorSimple Snapshot Manager のホスト名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backup.Validate " />
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