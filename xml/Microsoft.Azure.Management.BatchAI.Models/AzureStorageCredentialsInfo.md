<Type Name="AzureStorageCredentialsInfo" FullName="Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo">
  <TypeSignature Language="C#" Value="public class AzureStorageCredentialsInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureStorageCredentialsInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureStorageCredentialsInfo" />
  <TypeSignature Language="F#" Value="type AzureStorageCredentialsInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6b547-101">Azure のファイル共有へのアクセス資格情報です。</span><span class="sxs-lookup"><span data-stu-id="6b547-101">Credentials to access Azure File Share.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureStorageCredentialsInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6b547-102">AzureStorageCredentialsInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b547-102">Initializes a new instance of the AzureStorageCredentialsInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureStorageCredentialsInfo (string accountKey = null, Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference accountKeySecretReference = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountKey, class Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference accountKeySecretReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.#ctor(System.String,Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountKey As String = null, Optional accountKeySecretReference As KeyVaultSecretReference = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo : string * Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference -&gt; Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo" Usage="new Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo (accountKey, accountKeySecretReference)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountKey" Type="System.String" />
        <Parameter Name="accountKeySecretReference" Type="Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference" />
      </Parameters>
      <Docs>
        <param name="accountKey"><span data-ttu-id="6b547-103">ストレージ アカウント キー。</span><span class="sxs-lookup"><span data-stu-id="6b547-103">Storage account key.</span></span></param>
        <param name="accountKeySecretReference"><span data-ttu-id="6b547-104">Key Vault のシークレットは、ストレージ アカウント キーの場所を指定します。</span><span class="sxs-lookup"><span data-stu-id="6b547-104">Specifies the location of the storage account key, which is a Key Vault Secret.</span></span></param>
        <summary>
            <span data-ttu-id="6b547-105">AzureStorageCredentialsInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6b547-105">Initializes a new instance of the AzureStorageCredentialsInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountKey">
      <MemberSignature Language="C#" Value="public string AccountKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.AccountKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountKey As String" />
      <MemberSignature Language="F#" Value="member this.AccountKey : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.AccountKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b547-106">取得またはストレージ アカウント キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="6b547-106">Gets or sets storage account key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6b547-107">AccountKey または accountKeySecretReference のいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6b547-107">One of accountKey or accountKeySecretReference must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountKeySecretReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference AccountKeySecretReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference AccountKeySecretReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.AccountKeySecretReference" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountKeySecretReference As KeyVaultSecretReference" />
      <MemberSignature Language="F#" Value="member this.AccountKeySecretReference : Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.AccountKeySecretReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountKeySecretReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6b547-108">取得または設定は、Key Vault のシークレットは、ストレージ アカウント キーの場所を指定します。</span><span class="sxs-lookup"><span data-stu-id="6b547-108">Gets or sets specifies the location of the storage account key, which is a Key Vault Secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6b547-109">ユーザーが KeyVault と統合するバッチ AI サービスに渡すし、Azure KeyVault でそのシークレットを格納できます。</span><span class="sxs-lookup"><span data-stu-id="6b547-109">Users can store their secrets in Azure KeyVault and pass it to the Batch AI Service to integrate with KeyVault.</span></span> <span data-ttu-id="6b547-110">AccountKey または accountKeySecretReference のいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="6b547-110">One of accountKey or accountKeySecretReference must be specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AzureStorageCredentialsInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureStorageCredentialsInfo.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6b547-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6b547-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b547-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b547-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>