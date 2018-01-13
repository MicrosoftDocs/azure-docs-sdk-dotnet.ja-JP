<Type Name="DeletedCertificateBundle" FullName="Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle">
  <TypeSignature Language="C#" Value="public class DeletedCertificateBundle : Microsoft.Azure.KeyVault.Models.CertificateBundle" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedCertificateBundle extends Microsoft.Azure.KeyVault.Models.CertificateBundle" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedCertificateBundle&#xA;Inherits CertificateBundle" />
  <TypeSignature Language="F#" Value="type DeletedCertificateBundle = class&#xA;    inherit CertificateBundle" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Models.CertificateBundle</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            削除済み証明書、前の id、属性とそのタグと同様の消去する場合の情報で構成されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedCertificateBundle ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DeletedCertificateBundle クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedCertificateBundle (string id = null, string kid = null, string sid = null, byte[] x509Thumbprint = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy policy = null, byte[] cer = null, string contentType = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string recoveryId = null, Nullable&lt;DateTime&gt; scheduledPurgeDate = null, Nullable&lt;DateTime&gt; deletedDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string kid, string sid, unsigned int8[] x509Thumbprint, class Microsoft.Azure.KeyVault.Models.CertificatePolicy policy, unsigned int8[] cer, string contentType, class Microsoft.Azure.KeyVault.Models.CertificateAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string recoveryId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; scheduledPurgeDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; deletedDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.#ctor(System.String,System.String,System.String,System.Byte[],Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Byte[],System.String,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional kid As String = null, Optional sid As String = null, Optional x509Thumbprint As Byte() = null, Optional policy As CertificatePolicy = null, Optional cer As Byte() = null, Optional contentType As String = null, Optional attributes As CertificateAttributes = null, Optional tags As IDictionary(Of String, String) = null, Optional recoveryId As String = null, Optional scheduledPurgeDate As Nullable(Of DateTime) = null, Optional deletedDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle : string * string * string * byte[] * Microsoft.Azure.KeyVault.Models.CertificatePolicy * byte[] * string * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle" Usage="new Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle (id, kid, sid, x509Thumbprint, policy, cer, contentType, attributes, tags, recoveryId, scheduledPurgeDate, deletedDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="kid" Type="System.String" />
        <Parameter Name="sid" Type="System.String" />
        <Parameter Name="x509Thumbprint" Type="System.Byte[]" />
        <Parameter Name="policy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="cer" Type="System.Byte[]" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="scheduledPurgeDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="deletedDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id">証明書の id です。</param>
        <param name="kid">キーの id です。</param>
        <param name="sid">シークレットの id です。</param>
        <param name="x509Thumbprint">証明書の拇印です。</param>
        <param name="policy">管理ポリシー。</param>
        <param name="cer">CER 内容の x509 証明書。</param>
        <param name="contentType">シークレットのコンテンツの種類。</param>
        <param name="attributes">証明書の属性です。</param>
        <param name="tags">キー/値ペアの形式でのアプリケーション固有のメタデータ</param>
        <param name="recoveryId">識別し、削除された証明書を復旧するために使用、回復オブジェクトの url です。</param>
        <param name="scheduledPurgeDate">証明書が utc 形式で、消去する予定時刻</param>
        <param name="deletedDate">ときに、証明書が削除された utc 時刻</param>
        <summary>
            DeletedCertificateBundle クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DeletedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DeletedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.DeletedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DeletedDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.DeletedDate" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.RecoveryId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryId : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.RecoveryId" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.RecoveryIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryIdentifier As DeletedCertificateIdentifier" />
      <MemberSignature Language="F#" Value="member this.RecoveryIdentifier : Microsoft.Azure.KeyVault.DeletedCertificateIdentifier" Usage="Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.RecoveryIdentifier" />
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
            証明書が削除されたオブジェクトの識別子。 証明書を復旧に使用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledPurgeDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ScheduledPurgeDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ScheduledPurgeDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.ScheduledPurgeDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledPurgeDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ScheduledPurgeDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.ScheduledPurgeDate" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="deletedCertificateBundle.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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