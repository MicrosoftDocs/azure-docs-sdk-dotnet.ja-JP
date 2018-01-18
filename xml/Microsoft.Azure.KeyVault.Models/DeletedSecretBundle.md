<Type Name="DeletedSecretBundle" FullName="Microsoft.Azure.KeyVault.Models.DeletedSecretBundle">
  <TypeSignature Language="C#" Value="public class DeletedSecretBundle : Microsoft.Azure.KeyVault.Models.SecretBundle" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedSecretBundle extends Microsoft.Azure.KeyVault.Models.SecretBundle" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.DeletedSecretBundle" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedSecretBundle&#xA;Inherits SecretBundle" />
  <TypeSignature Language="F#" Value="type DeletedSecretBundle = class&#xA;    inherit SecretBundle" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Models.SecretBundle</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f51e-101">その前の id、属性とそのタグと同様の消去する場合の情報で構成される、削除のシークレット。</span><span class="sxs-lookup"><span data-stu-id="8f51e-101">A Deleted Secret consisting of its previous id, attributes and its tags, as well as information on when it will be purged.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedSecretBundle ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedSecretBundle.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8f51e-102">DeletedSecretBundle クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8f51e-102">Initializes a new instance of the DeletedSecretBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedSecretBundle (string value = null, string id = null, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string kid = null, Nullable&lt;bool&gt; managed = null, string recoveryId = null, Nullable&lt;DateTime&gt; scheduledPurgeDate = null, Nullable&lt;DateTime&gt; deletedDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value, string id, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string kid, valuetype System.Nullable`1&lt;bool&gt; managed, string recoveryId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; scheduledPurgeDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; deletedDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.DeletedSecretBundle.#ctor(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.Boolean},System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As String = null, Optional id As String = null, Optional contentType As String = null, Optional attributes As SecretAttributes = null, Optional tags As IDictionary(Of String, String) = null, Optional kid As String = null, Optional managed As Nullable(Of Boolean) = null, Optional recoveryId As String = null, Optional scheduledPurgeDate As Nullable(Of DateTime) = null, Optional deletedDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.DeletedSecretBundle : string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;bool&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.KeyVault.Models.DeletedSecretBundle" Usage="new Microsoft.Azure.KeyVault.Models.DeletedSecretBundle (value, id, contentType, attributes, tags, kid, managed, recoveryId, scheduledPurgeDate, deletedDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="kid" Type="System.String" />
        <Parameter Name="managed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="scheduledPurgeDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="deletedDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="8f51e-103">シークレットの値です。</span><span class="sxs-lookup"><span data-stu-id="8f51e-103">The secret value.</span></span></param>
        <param name="id"><span data-ttu-id="8f51e-104">シークレットの id です。</span><span class="sxs-lookup"><span data-stu-id="8f51e-104">The secret id.</span></span></param>
        <param name="contentType"><span data-ttu-id="8f51e-105">シークレットのコンテンツの種類。</span><span class="sxs-lookup"><span data-stu-id="8f51e-105">The content type of the secret.</span></span></param>
        <param name="attributes"><span data-ttu-id="8f51e-106">シークレットの管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="8f51e-106">The secret management attributes.</span></span></param>
        <param name="tags"><span data-ttu-id="8f51e-107">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="8f51e-107">Application specific metadata in the form of key-value pairs.</span></span></param>
        <param name="kid"><span data-ttu-id="8f51e-108">KV 証明書をバックアップするシークレットの場合は、このフィールドは KV 証明書をバックアップ、対応するキーを指定します。</span><span class="sxs-lookup"><span data-stu-id="8f51e-108">If this is a secret backing a KV certificate, then this field specifies the corresponding key backing the KV certificate.</span></span></param>
        <param name="managed"><span data-ttu-id="8f51e-109">シークレットの有効期間が資格情報コンテナーで管理されている場合は true。</span><span class="sxs-lookup"><span data-stu-id="8f51e-109">True if the secret's lifetime is managed by key vault.</span></span> <span data-ttu-id="8f51e-110">これは、シークレットのバックアップし、管理、証明書が true になります。</span><span class="sxs-lookup"><span data-stu-id="8f51e-110">If this is a secret backing a certificate, then managed will be true.</span></span></param>
        <param name="recoveryId"><span data-ttu-id="8f51e-111">識別し、削除されたシークレットを復元するために使用、回復オブジェクトの url です。</span><span class="sxs-lookup"><span data-stu-id="8f51e-111">The url of the recovery object, used to identify and recover the deleted secret.</span></span></param>
        <param name="scheduledPurgeDate"><span data-ttu-id="8f51e-112">シークレットが utc 形式で、消去する予定時刻</span><span class="sxs-lookup"><span data-stu-id="8f51e-112">The time when the secret is scheduled to be purged, in UTC</span></span></param>
        <param name="deletedDate"><span data-ttu-id="8f51e-113">ときに、シークレットが削除された utc 時刻</span><span class="sxs-lookup"><span data-stu-id="8f51e-113">The time when the secret was deleted, in UTC</span></span></param>
        <summary>
            <span data-ttu-id="8f51e-114">DeletedSecretBundle クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8f51e-114">Initializes a new instance of the DeletedSecretBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DeletedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DeletedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedSecretBundle.DeletedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DeletedDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.DeletedSecretBundle.DeletedDate" />
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
            <span data-ttu-id="8f51e-115">ときに、シークレットが削除された utc 時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="8f51e-115">Gets the time when the secret was deleted, in UTC</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryId">
      <MemberSignature Language="C#" Value="public string RecoveryId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedSecretBundle.RecoveryId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryId : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.DeletedSecretBundle.RecoveryId" />
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
            <span data-ttu-id="8f51e-116">取得または識別し、削除されたシークレットを復元するために使用、回復オブジェクトの url を設定します。</span><span class="sxs-lookup"><span data-stu-id="8f51e-116">Gets or sets the url of the recovery object, used to identify and recover the deleted secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.DeletedSecretIdentifier RecoveryIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.DeletedSecretIdentifier RecoveryIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedSecretBundle.RecoveryIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryIdentifier As DeletedSecretIdentifier" />
      <MemberSignature Language="F#" Value="member this.RecoveryIdentifier : Microsoft.Azure.KeyVault.DeletedSecretIdentifier" Usage="Microsoft.Azure.KeyVault.Models.DeletedSecretBundle.RecoveryIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.DeletedSecretIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f51e-117">削除されたシークレット オブジェクトの識別子。</span><span class="sxs-lookup"><span data-stu-id="8f51e-117">The identifier of the deleted secret object.</span></span> <span data-ttu-id="8f51e-118">シークレットの復元に使用されます。</span><span class="sxs-lookup"><span data-stu-id="8f51e-118">This is used to recover the secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledPurgeDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ScheduledPurgeDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ScheduledPurgeDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.DeletedSecretBundle.ScheduledPurgeDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledPurgeDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ScheduledPurgeDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.KeyVault.Models.DeletedSecretBundle.ScheduledPurgeDate" />
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
            <span data-ttu-id="8f51e-119">シークレットが utc 形式で、消去する予定時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="8f51e-119">Gets the time when the secret is scheduled to be purged, in UTC</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>