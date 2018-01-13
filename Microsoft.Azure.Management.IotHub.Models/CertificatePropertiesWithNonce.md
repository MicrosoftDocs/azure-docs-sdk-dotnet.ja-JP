<Type Name="CertificatePropertiesWithNonce" FullName="Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce">
  <TypeSignature Language="C#" Value="public class CertificatePropertiesWithNonce" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificatePropertiesWithNonce extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificatePropertiesWithNonce" />
  <TypeSignature Language="F#" Value="type CertificatePropertiesWithNonce = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            所有証明のフローのチャレンジ nonce を含む CA 証明書が発行された X509 の説明です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificatePropertiesWithNonce ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CertificatePropertiesWithNonce クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificatePropertiesWithNonce (string subject = null, Nullable&lt;DateTime&gt; expiry = null, string thumbprint = null, Nullable&lt;bool&gt; isVerified = null, Nullable&lt;DateTime&gt; created = null, Nullable&lt;DateTime&gt; updated = null, string verificationCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string subject, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiry, string thumbprint, valuetype System.Nullable`1&lt;bool&gt; isVerified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updated, string verificationCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.#ctor(System.String,System.Nullable{System.DateTime},System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional subject As String = null, Optional expiry As Nullable(Of DateTime) = null, Optional thumbprint As String = null, Optional isVerified As Nullable(Of Boolean) = null, Optional created As Nullable(Of DateTime) = null, Optional updated As Nullable(Of DateTime) = null, Optional verificationCode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce : string * Nullable&lt;DateTime&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce" Usage="new Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce (subject, expiry, thumbprint, isVerified, created, updated, verificationCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="subject" Type="System.String" />
        <Parameter Name="expiry" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="isVerified" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updated" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="verificationCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="subject">証明書のサブジェクト名。</param>
        <param name="expiry">証明書の有効期限の日付と時刻。</param>
        <param name="thumbprint">証明書の拇印です。</param>
        <param name="isVerified">証明書が検証されているかどうかを判断します。</param>
        <param name="created">証明書の日付と時刻を作成します。</param>
        <param name="updated">証明書の最終更新日付と時刻。</param>
        <param name="verificationCode">所有権の証明に使用される証明書の確認コード。</param>
        <summary>
            CertificatePropertiesWithNonce クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Created { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Created" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.Created" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Created As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Created : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.Created" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="created")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、証明書は、日付と時刻を作成します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expiry">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Expiry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Expiry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.Expiry" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Expiry As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Expiry : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.Expiry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expiry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書の有効期限の日付と時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsVerified">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsVerified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsVerified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.IsVerified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsVerified As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsVerified : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.IsVerified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isVerified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、証明書が検証されているかどうかを判断します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subject">
      <MemberSignature Language="C#" Value="public string Subject { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subject" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.Subject" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subject As String" />
      <MemberSignature Language="F#" Value="member this.Subject : string" Usage="Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.Subject" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subject")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書のサブジェクト名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書の拇印を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Updated">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Updated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Updated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.Updated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Updated As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Updated : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.Updated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="updated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書の最終更新日付と時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerificationCode">
      <MemberSignature Language="C#" Value="public string VerificationCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VerificationCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.VerificationCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VerificationCode As String" />
      <MemberSignature Language="F#" Value="member this.VerificationCode : string" Usage="Microsoft.Azure.Management.IotHub.Models.CertificatePropertiesWithNonce.VerificationCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="verificationCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            所有権の証明に使用される証明書の検証コードを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>