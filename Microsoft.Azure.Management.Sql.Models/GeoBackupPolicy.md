<Type Name="GeoBackupPolicy" FullName="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy">
  <TypeSignature Language="C#" Value="public class GeoBackupPolicy : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GeoBackupPolicy extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class GeoBackupPolicy&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type GeoBackupPolicy = class&#xA;    inherit ProxyResource" />
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
            データベース geo バックアップ ポリシーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoBackupPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            GeoBackupPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoBackupPolicy (Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState state, string id = null, string name = null, string type = null, string storageType = null, string kind = null, string location = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState state, string id, string name, string type, string storageType, string kind, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.#ctor(Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As GeoBackupPolicyState, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional storageType As String = null, Optional kind As String = null, Optional location As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy : Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" Usage="new Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy (state, id, name, type, storageType, kind, location)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="storageType" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="state">Geo バックアップ ポリシーの状態。 使用可能な値が含まれます: '無効'、'Enabled'</param>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="storageType">Geo バックアップ ポリシーの記憶域の種類。</param>
        <param name="kind">Geo バックアップ ポリシーの種類。  これは、Azure ポータルのエクスペリエンスで使用されるメタデータです。</param>
        <param name="location">バックアップ ポリシーの場所です。</param>
        <summary>
            GeoBackupPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Geo バックアップ ポリシーの種類を取得。  これは、Azure ポータルのエクスペリエンスで使用されるメタデータです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.Location" />
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
            バックアップ ポリシーの場所を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As GeoBackupPolicyState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState with get, set" Usage="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.State" />
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
        <ReturnType>Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または geo バックアップ ポリシーの状態を設定します。 使用可能な値が含まれます: '無効'、'Enabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageType">
      <MemberSignature Language="C#" Value="public string StorageType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.StorageType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageType As String" />
      <MemberSignature Language="F#" Value="member this.StorageType : string" Usage="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.StorageType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Geo バックアップ ポリシーの記憶域の種類を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="geoBackupPolicy.Validate " />
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