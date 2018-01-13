<Type Name="DeletedCertificateItem" FullName="Microsoft.Azure.KeyVault.Models.DeletedCertificateItem">
  <TypeSignature Language="C#" Value="public class DeletedCertificateItem : Microsoft.Azure.KeyVault.Models.CertificateItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedCertificateItem extends Microsoft.Azure.KeyVault.Models.CertificateItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.DeletedCertificateItem" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedCertificateItem&#xA;Inherits CertificateItem" />
  <TypeSignature Language="F#" Value="type DeletedCertificateItem = class&#xA;    inherit CertificateItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Models.CertificateItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            削除済みの証明書に関するメタデータを含む証明書が削除された項目。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedCertificateItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedCertificateItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DeletedCertificateItem クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedCertificateItem (string id = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, byte[] x509Thumbprint = null, string recoveryId = null, Nullable&lt;DateTime&gt; scheduledPurgeDate = null, Nullable&lt;DateTime&gt; deletedDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.KeyVault.Models.CertificateAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, unsigned int8[] x509Thumbprint, string recoveryId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; scheduledPurgeDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; deletedDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedCertificateItem.#ctor(System.String,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Byte[],System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional attributes As CertificateAttributes = null, Optional tags As IDictionary(Of String, String) = null, Optional x509Thumbprint As Byte() = null, Optional recoveryId As String = null, Optional scheduledPurgeDate As Nullable(Of DateTime) = null, Optional deletedDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.DeletedCertificateItem : string * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * byte[] * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.KeyVault.Models.DeletedCertificateItem" Usage="new Microsoft.Azure.KeyVault.Models.DeletedCertificateItem (id, attributes, tags, x509Thumbprint, recoveryId, scheduledPurgeDate, deletedDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="x509Thumbprint" Type="System.Byte[]" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="scheduledPurgeDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="deletedDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id">証明書識別子です。</param>
        <param name="attributes">証明書管理の属性です。</param>
        <param name="tags">キー/値ペアの形式でのアプリケーション固有のメタデータ。</param>
        <param name="x509Thumbprint">証明書の拇印です。</param>
        <param name="recoveryId">識別し、削除された証明書を復旧するために使用、回復オブジェクトの url です。</param>
        <param name="scheduledPurgeDate">証明書が utc 形式で、消去する予定時刻</param>
        <param name="deletedDate">ときに、証明書が削除された utc 時刻</param>
        <summary>
            DeletedCertificateItem クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DeletedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DeletedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedCertificateItem.DeletedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DeletedDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.DeletedCertificateItem.DeletedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.UnixTimeJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deletedDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ときに、証明書が削除された utc 時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryId">
      <MemberSignature Language="C#" Value="public string RecoveryId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedCertificateItem.RecoveryId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryId : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.DeletedCertificateItem.RecoveryId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または識別し、削除された証明書を復旧するために使用、回復オブジェクトの url を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.DeletedCertificateIdentifier RecoveryIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.DeletedCertificateIdentifier RecoveryIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedCertificateItem.RecoveryIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryIdentifier As DeletedCertificateIdentifier" />
      <MemberSignature Language="F#" Value="member this.RecoveryIdentifier : Microsoft.Azure.KeyVault.DeletedCertificateIdentifier" Usage="Microsoft.Azure.KeyVault.Models.DeletedCertificateItem.RecoveryIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.DeletedCertificateIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            削除されたシークレット オブジェクトの識別子。 シークレットの復元に使用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledPurgeDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ScheduledPurgeDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ScheduledPurgeDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedCertificateItem.ScheduledPurgeDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledPurgeDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ScheduledPurgeDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.DeletedCertificateItem.ScheduledPurgeDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.UnixTimeJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scheduledPurgeDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書が utc 形式で、消去する予定時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>