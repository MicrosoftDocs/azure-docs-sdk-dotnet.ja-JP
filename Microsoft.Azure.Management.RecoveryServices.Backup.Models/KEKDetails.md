<Type Name="KEKDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails">
  <TypeSignature Language="C#" Value="public class KEKDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KEKDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class KEKDetails" />
  <TypeSignature Language="F#" Value="type KEKDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fdfab-101">KEK は BEK の暗号化キーです。</span><span class="sxs-lookup"><span data-stu-id="fdfab-101">KEK is encryption key for BEK.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KEKDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fdfab-102">KEKDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdfab-102">Initializes a new instance of the KEKDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KEKDetails (string keyUrl = null, string keyVaultId = null, string keyBackupData = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyUrl, string keyVaultId, string keyBackupData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional keyUrl As String = null, Optional keyVaultId As String = null, Optional keyBackupData As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails : string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails (keyUrl, keyVaultId, keyBackupData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyUrl" Type="System.String" />
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="keyBackupData" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyUrl"><span data-ttu-id="fdfab-103">キーは、KEK です。</span><span class="sxs-lookup"><span data-stu-id="fdfab-103">Key is KEK.</span></span></param>
        <param name="keyVaultId"><span data-ttu-id="fdfab-104">このキーが格納されているキー資格情報コンテナーの ID です。</span><span class="sxs-lookup"><span data-stu-id="fdfab-104">Key Vault ID where this Key is stored.</span></span></param>
        <param name="keyBackupData"><span data-ttu-id="fdfab-105">KEK データ。</span><span class="sxs-lookup"><span data-stu-id="fdfab-105">KEK data.</span></span></param>
        <summary>
            <span data-ttu-id="fdfab-106">KEKDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fdfab-106">Initializes a new instance of the KEKDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyBackupData">
      <MemberSignature Language="C#" Value="public string KeyBackupData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyBackupData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyBackupData" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyBackupData As String" />
      <MemberSignature Language="F#" Value="member this.KeyBackupData : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyBackupData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyBackupData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdfab-107">取得または KEK データを設定します。</span><span class="sxs-lookup"><span data-stu-id="fdfab-107">Gets or sets KEK data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyUrl">
      <MemberSignature Language="C#" Value="public string KeyUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyUrl As String" />
      <MemberSignature Language="F#" Value="member this.KeyUrl : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdfab-108">取得または設定キーは、KEK です。</span><span class="sxs-lookup"><span data-stu-id="fdfab-108">Gets or sets key is KEK.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultId">
      <MemberSignature Language="C#" Value="public string KeyVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultId As String" />
      <MemberSignature Language="F#" Value="member this.KeyVaultId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.KEKDetails.KeyVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdfab-109">取得またはこのキーが格納されている資格情報コンテナーの ID キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="fdfab-109">Gets or sets key Vault ID where this Key is stored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>