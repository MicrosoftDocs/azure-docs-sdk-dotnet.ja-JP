<Type Name="DeletedKeyBundle" FullName="Microsoft.Azure.KeyVault.Models.DeletedKeyBundle">
  <TypeSignature Language="C#" Value="public class DeletedKeyBundle : Microsoft.Azure.KeyVault.Models.KeyBundle" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedKeyBundle extends Microsoft.Azure.KeyVault.Models.KeyBundle" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.DeletedKeyBundle" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedKeyBundle&#xA;Inherits KeyBundle" />
  <TypeSignature Language="F#" Value="type DeletedKeyBundle = class&#xA;    inherit KeyBundle" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Models.KeyBundle</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c569f-101">WebKey とその属性と削除情報で構成される DeletedKeyBundle</span><span class="sxs-lookup"><span data-stu-id="c569f-101">A DeletedKeyBundle consisting of a WebKey plus its Attributes and deletion info</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedKeyBundle ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedKeyBundle.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c569f-102">DeletedKeyBundle クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c569f-102">Initializes a new instance of the DeletedKeyBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedKeyBundle (Microsoft.Azure.KeyVault.WebKey.JsonWebKey key = null, Microsoft.Azure.KeyVault.Models.KeyAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;bool&gt; managed = null, string recoveryId = null, Nullable&lt;DateTime&gt; scheduledPurgeDate = null, Nullable&lt;DateTime&gt; deletedDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, class Microsoft.Azure.KeyVault.Models.KeyAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;bool&gt; managed, string recoveryId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; scheduledPurgeDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; deletedDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedKeyBundle.#ctor(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional key As JsonWebKey = null, Optional attributes As KeyAttributes = null, Optional tags As IDictionary(Of String, String) = null, Optional managed As Nullable(Of Boolean) = null, Optional recoveryId As String = null, Optional scheduledPurgeDate As Nullable(Of DateTime) = null, Optional deletedDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.DeletedKeyBundle : Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.KeyVault.Models.DeletedKeyBundle" Usage="new Microsoft.Azure.KeyVault.Models.DeletedKeyBundle (key, attributes, tags, managed, recoveryId, scheduledPurgeDate, deletedDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="managed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="scheduledPurgeDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="deletedDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="c569f-103">Json web キー。</span><span class="sxs-lookup"><span data-stu-id="c569f-103">The Json web key.</span></span></param>
        <param name="attributes"><span data-ttu-id="c569f-104">キー管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="c569f-104">The key management attributes.</span></span></param>
        <param name="tags"><span data-ttu-id="c569f-105">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="c569f-105">Application specific metadata in the form of key-value pairs.</span></span></param>
        <param name="managed"><span data-ttu-id="c569f-106">キーの有効期間が資格情報コンテナーで管理されている場合は true。</span><span class="sxs-lookup"><span data-stu-id="c569f-106">True if the key's lifetime is managed by key vault.</span></span> <span data-ttu-id="c569f-107">これは、キーのバックアップし、管理、証明書が true になります。</span><span class="sxs-lookup"><span data-stu-id="c569f-107">If this is a key backing a certificate, then managed will be true.</span></span></param>
        <param name="recoveryId"><span data-ttu-id="c569f-108">識別し、削除されたキーを回復するために使用、回復オブジェクトの url です。</span><span class="sxs-lookup"><span data-stu-id="c569f-108">The url of the recovery object, used to identify and recover the deleted key.</span></span></param>
        <param name="scheduledPurgeDate"><span data-ttu-id="c569f-109">キーが utc 形式で、消去する予定時刻</span><span class="sxs-lookup"><span data-stu-id="c569f-109">The time when the key is scheduled to be purged, in UTC</span></span></param>
        <param name="deletedDate"><span data-ttu-id="c569f-110">キーが削除されたとき、utc 時刻</span><span class="sxs-lookup"><span data-stu-id="c569f-110">The time when the key was deleted, in UTC</span></span></param>
        <summary>
            <span data-ttu-id="c569f-111">DeletedKeyBundle クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c569f-111">Initializes a new instance of the DeletedKeyBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DeletedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DeletedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedKeyBundle.DeletedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DeletedDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.DeletedKeyBundle.DeletedDate" />
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
            <span data-ttu-id="c569f-112">キーが削除されたとき、utc 時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c569f-112">Gets the time when the key was deleted, in UTC</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryId">
      <MemberSignature Language="C#" Value="public string RecoveryId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedKeyBundle.RecoveryId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryId : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.DeletedKeyBundle.RecoveryId" />
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
            <span data-ttu-id="c569f-113">取得または識別し、削除されたキーを回復するために使用、回復オブジェクトの url を設定します。</span><span class="sxs-lookup"><span data-stu-id="c569f-113">Gets or sets the url of the recovery object, used to identify and recover the deleted key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.DeletedKeyIdentifier RecoveryIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.DeletedKeyIdentifier RecoveryIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedKeyBundle.RecoveryIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryIdentifier As DeletedKeyIdentifier" />
      <MemberSignature Language="F#" Value="member this.RecoveryIdentifier : Microsoft.Azure.KeyVault.DeletedKeyIdentifier" Usage="Microsoft.Azure.KeyVault.Models.DeletedKeyBundle.RecoveryIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.DeletedKeyIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c569f-114">削除されたキー オブジェクトの識別子。</span><span class="sxs-lookup"><span data-stu-id="c569f-114">The identifier of the deleted key object.</span></span> <span data-ttu-id="c569f-115">これは、キーの回復に使用されます。</span><span class="sxs-lookup"><span data-stu-id="c569f-115">This is used to recover the key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledPurgeDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ScheduledPurgeDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ScheduledPurgeDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedKeyBundle.ScheduledPurgeDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledPurgeDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ScheduledPurgeDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.DeletedKeyBundle.ScheduledPurgeDate" />
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
            <span data-ttu-id="c569f-116">キーが utc 形式で、消去する予定時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c569f-116">Gets the time when the key is scheduled to be purged, in UTC</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>