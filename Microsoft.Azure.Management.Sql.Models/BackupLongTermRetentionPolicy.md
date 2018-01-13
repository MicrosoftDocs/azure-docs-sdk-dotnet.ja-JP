<Type Name="BackupLongTermRetentionPolicy" FullName="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy">
  <TypeSignature Language="C#" Value="public class BackupLongTermRetentionPolicy : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupLongTermRetentionPolicy extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupLongTermRetentionPolicy&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type BackupLongTermRetentionPolicy = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            バックアップの長期的な保有期間ポリシー
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupLongTermRetentionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackupLongTermRetentionPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupLongTermRetentionPolicy (Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState state, string recoveryServicesBackupPolicyResourceId, string id = null, string name = null, string type = null, string location = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState state, string recoveryServicesBackupPolicyResourceId, string id, string name, string type, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.#ctor(Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As BackupLongTermRetentionPolicyState, recoveryServicesBackupPolicyResourceId As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy : Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" Usage="new Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy (state, recoveryServicesBackupPolicyResourceId, id, name, type, location)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState" />
        <Parameter Name="recoveryServicesBackupPolicyResourceId" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="state">バックアップの長期的な保有期間ポリシーの状態です。 使用可能な値が含まれます: '無効'、'Enabled'</param>
        <param name="recoveryServicesBackupPolicyResourceId">Azure 回復サービスをバックアップ ポリシーのリソース id の保護</param>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="location">リソースが存在する地理的な場所</param>
        <summary>
            BackupLongTermRetentionPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リソースが存在する地理的な場所を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryServicesBackupPolicyResourceId">
      <MemberSignature Language="C#" Value="public string RecoveryServicesBackupPolicyResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryServicesBackupPolicyResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.RecoveryServicesBackupPolicyResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryServicesBackupPolicyResourceId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryServicesBackupPolicyResourceId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.RecoveryServicesBackupPolicyResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recoveryServicesBackupPolicyResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure 回復サービスのバックアップ保護ポリシー リソース id 取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As BackupLongTermRetentionPolicyState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState with get, set" Usage="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップの長期的な保有期間ポリシーの状態を設定します。
            使用可能な値が含まれます: '無効'、'Enabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupLongTermRetentionPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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