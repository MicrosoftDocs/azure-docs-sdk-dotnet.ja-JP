<Type Name="BackupRequestResource" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource">
  <TypeSignature Language="C#" Value="public class BackupRequestResource : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupRequestResource extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupRequestResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BackupRequestResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            バックアップのリクエストの基本クラス。 ワークロードに固有のバックアップ要求は、このクラスから派生します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupRequestResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackupRequestResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupRequestResource (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string eTag = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string eTag, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional eTag As String = null, Optional properties As BackupRequest = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource (id, name, type, location, tags, eTag, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id は、リソースへの完全なパスを表します。</param>
        <param name="name">リソースに関連付けられているリソースの名前です。</param>
        <param name="type">リソースの種類は Namespace/ResourceType/ResourceType/... 形式の完全なパスを表します</param>
        <param name="location">リソースの場所。</param>
        <param name="tags">リソース タグ。</param>
        <param name="eTag">省略可能な ETag です。</param>
        <param name="properties">BackupRequestResource プロパティ</param>
        <summary>
            BackupRequestResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As BackupRequest" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequestResource.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 backupRequestResource プロパティ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>