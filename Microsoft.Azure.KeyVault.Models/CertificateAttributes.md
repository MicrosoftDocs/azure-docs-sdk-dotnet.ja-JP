<Type Name="CertificateAttributes" FullName="Microsoft.Azure.KeyVault.Models.CertificateAttributes">
  <TypeSignature Language="C#" Value="public class CertificateAttributes : Microsoft.Azure.KeyVault.Models.Attributes" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateAttributes extends Microsoft.Azure.KeyVault.Models.Attributes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateAttributes&#xA;Inherits Attributes" />
  <TypeSignature Language="F#" Value="type CertificateAttributes = class&#xA;    inherit Attributes" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Models.Attributes</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4a561-101">証明書管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="4a561-101">The certificate management attributes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateAttributes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateAttributes.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4a561-102">CertificateAttributes クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4a561-102">Initializes a new instance of the CertificateAttributes class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateAttributes (Nullable&lt;bool&gt; enabled = null, Nullable&lt;DateTime&gt; notBefore = null, Nullable&lt;DateTime&gt; expires = null, Nullable&lt;DateTime&gt; created = null, Nullable&lt;DateTime&gt; updated = null, string recoveryLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; notBefore, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expires, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updated, string recoveryLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateAttributes.#ctor(System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional notBefore As Nullable(Of DateTime) = null, Optional expires As Nullable(Of DateTime) = null, Optional created As Nullable(Of DateTime) = null, Optional updated As Nullable(Of DateTime) = null, Optional recoveryLevel As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateAttributes : Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.KeyVault.Models.CertificateAttributes" Usage="new Microsoft.Azure.KeyVault.Models.CertificateAttributes (enabled, notBefore, expires, created, updated, recoveryLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="notBefore" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expires" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updated" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryLevel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="4a561-103">オブジェクトが有効になっているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="4a561-103">Determines whether the object is enabled.</span></span></param>
        <param name="notBefore"><span data-ttu-id="4a561-104">期間の開始時刻 (utc) 日付です。</span><span class="sxs-lookup"><span data-stu-id="4a561-104">Not before date in UTC.</span></span></param>
        <param name="expires"><span data-ttu-id="4a561-105">有効期限日 (utc)。</span><span class="sxs-lookup"><span data-stu-id="4a561-105">Expiry date in UTC.</span></span></param>
        <param name="created"><span data-ttu-id="4a561-106">作成時刻 (utc) です。</span><span class="sxs-lookup"><span data-stu-id="4a561-106">Creation time in UTC.</span></span></param>
        <param name="updated"><span data-ttu-id="4a561-107">最終更新時刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="4a561-107">Last updated time in UTC.</span></span></param>
        <param name="recoveryLevel"><span data-ttu-id="4a561-108">削除回復のレベルは、現在有効で、現在の資格情報コンテナー内の証明書が反映されます。</span><span class="sxs-lookup"><span data-stu-id="4a561-108">Reflects the deletion recovery level currently in effect for certificates in the current vault.</span></span> <span data-ttu-id="4a561-109">特権を持つユーザーは、証明書を完全に削除 'Purgeable' が含まれている場合それ以外の場合、システムだけでは、保有期間の最後に、証明書を削除できます。</span><span class="sxs-lookup"><span data-stu-id="4a561-109">If it contains 'Purgeable', the certificate can be permanently deleted by a privileged user; otherwise, only the system can purge the certificate, at the end of the retention interval.</span></span> <span data-ttu-id="4a561-110">使用可能な値が含まれます: 'パージ可能な'、' 回復可能な + Purgeable'、'回復可能な'、' 回復可能な + ProtectedSubscription'</span><span class="sxs-lookup"><span data-stu-id="4a561-110">Possible values include: 'Purgeable', 'Recoverable+Purgeable', 'Recoverable', 'Recoverable+ProtectedSubscription'</span></span></param>
        <summary>
            <span data-ttu-id="4a561-111">CertificateAttributes クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4a561-111">Initializes a new instance of the CertificateAttributes class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryLevel">
      <MemberSignature Language="C#" Value="public string RecoveryLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateAttributes.RecoveryLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryLevel As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryLevel : string" Usage="Microsoft.Azure.KeyVault.Models.CertificateAttributes.RecoveryLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4a561-112">取得には、削除回復のレベルは、現在有効で、現在の資格情報コンテナー内の証明書が反映されます。</span><span class="sxs-lookup"><span data-stu-id="4a561-112">Gets reflects the deletion recovery level currently in effect for certificates in the current vault.</span></span> <span data-ttu-id="4a561-113">特権を持つユーザーは、証明書を完全に削除 'Purgeable' が含まれている場合それ以外の場合、システムだけでは、保有期間の最後に、証明書を削除できます。</span><span class="sxs-lookup"><span data-stu-id="4a561-113">If it contains 'Purgeable', the certificate can be permanently deleted by a privileged user; otherwise, only the system can purge the certificate, at the end of the retention interval.</span></span> <span data-ttu-id="4a561-114">使用可能な値が含まれます: 'パージ可能な'、' 回復可能な + Purgeable'、'回復可能な'、' 回復可能な + ProtectedSubscription'</span><span class="sxs-lookup"><span data-stu-id="4a561-114">Possible values include: 'Purgeable', 'Recoverable+Purgeable', 'Recoverable', 'Recoverable+ProtectedSubscription'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>