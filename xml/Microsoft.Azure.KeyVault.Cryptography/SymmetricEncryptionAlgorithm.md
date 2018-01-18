<Type Name="SymmetricEncryptionAlgorithm" FullName="Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm">
  <TypeSignature Language="C#" Value="public abstract class SymmetricEncryptionAlgorithm : Microsoft.Azure.KeyVault.Cryptography.EncryptionAlgorithm" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SymmetricEncryptionAlgorithm extends Microsoft.Azure.KeyVault.Cryptography.EncryptionAlgorithm" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SymmetricEncryptionAlgorithm&#xA;Inherits EncryptionAlgorithm" />
  <TypeSignature Language="F#" Value="type SymmetricEncryptionAlgorithm = class&#xA;    inherit EncryptionAlgorithm" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Cryptography.EncryptionAlgorithm</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8759a-101">抽象 SymmetricEncryption アルゴリズム</span><span class="sxs-lookup"><span data-stu-id="8759a-101">Abstract SymmetricEncryption Algorithm</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SymmetricEncryptionAlgorithm (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm : string -&gt; Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm" Usage="new Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDecryptor">
      <MemberSignature Language="C#" Value="public abstract System.Security.Cryptography.ICryptoTransform CreateDecryptor (byte[] key, byte[] iv, byte[] authenticationData, byte[] authenticationTag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Security.Cryptography.ICryptoTransform CreateDecryptor(unsigned int8[] key, unsigned int8[] iv, unsigned int8[] authenticationData, unsigned int8[] authenticationTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm.CreateDecryptor(System.Byte[],System.Byte[],System.Byte[],System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateDecryptor (key As Byte(), iv As Byte(), authenticationData As Byte(), authenticationTag As Byte()) As ICryptoTransform" />
      <MemberSignature Language="F#" Value="abstract member CreateDecryptor : byte[] * byte[] * byte[] * byte[] -&gt; System.Security.Cryptography.ICryptoTransform" Usage="symmetricEncryptionAlgorithm.CreateDecryptor (key, iv, authenticationData, authenticationTag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.ICryptoTransform</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Byte[]" />
        <Parameter Name="iv" Type="System.Byte[]" />
        <Parameter Name="authenticationData" Type="System.Byte[]" />
        <Parameter Name="authenticationTag" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="8759a-102">使用されるキー マテリアル</span><span class="sxs-lookup"><span data-stu-id="8759a-102">The key material to be used</span></span></param>
        <param name="iv"><span data-ttu-id="8759a-103">使用する初期化ベクター</span><span class="sxs-lookup"><span data-stu-id="8759a-103">The initialization vector to be used</span></span></param>
        <param name="authenticationData"><span data-ttu-id="8759a-104">暗号化アルゴリズムの認証に使用する認証データ (非認証するため無視アルゴリズム)</span><span class="sxs-lookup"><span data-stu-id="8759a-104">The authentication data to be used with authenticating encryption algorithms (ignored for non-authenticating algorithms)</span></span></param>
        <param name="authenticationTag"><span data-ttu-id="8759a-105">認証の暗号化アルゴリズムを使用していることを確認する認証タグ (非認証するため無視アルゴリズム)</span><span class="sxs-lookup"><span data-stu-id="8759a-105">The authentication tag to verify when using authenticating encryption algorithms (ignored for non-authenticating algorithms)</span></span></param>
        <summary>
            <span data-ttu-id="8759a-106">指定されたキーの復号化を作成します。</span><span class="sxs-lookup"><span data-stu-id="8759a-106">Create a decryptor for the specified key</span></span>
            </summary>
        <returns><span data-ttu-id="8759a-107">データを復号化、ICryptoTransform</span><span class="sxs-lookup"><span data-stu-id="8759a-107">An ICryptoTransform for decrypting data</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEncryptor">
      <MemberSignature Language="C#" Value="public abstract System.Security.Cryptography.ICryptoTransform CreateEncryptor (byte[] key, byte[] iv, byte[] authenticationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Security.Cryptography.ICryptoTransform CreateEncryptor(unsigned int8[] key, unsigned int8[] iv, unsigned int8[] authenticationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm.CreateEncryptor(System.Byte[],System.Byte[],System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateEncryptor (key As Byte(), iv As Byte(), authenticationData As Byte()) As ICryptoTransform" />
      <MemberSignature Language="F#" Value="abstract member CreateEncryptor : byte[] * byte[] * byte[] -&gt; System.Security.Cryptography.ICryptoTransform" Usage="symmetricEncryptionAlgorithm.CreateEncryptor (key, iv, authenticationData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.ICryptoTransform</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Byte[]" />
        <Parameter Name="iv" Type="System.Byte[]" />
        <Parameter Name="authenticationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="8759a-108">使用されるキー マテリアル</span><span class="sxs-lookup"><span data-stu-id="8759a-108">The key material to be used</span></span></param>
        <param name="iv"><span data-ttu-id="8759a-109">使用する初期化ベクター</span><span class="sxs-lookup"><span data-stu-id="8759a-109">The initialization vector to be used</span></span></param>
        <param name="authenticationData"><span data-ttu-id="8759a-110">暗号化アルゴリズムの認証に使用する認証データ (非認証するため無視アルゴリズム)</span><span class="sxs-lookup"><span data-stu-id="8759a-110">The authentication data to be used with authenticating encryption algorithms (ignored for non-authenticating algorithms)</span></span></param>
        <summary>
            <span data-ttu-id="8759a-111">指定されたキーの暗号化機能を作成します。</span><span class="sxs-lookup"><span data-stu-id="8759a-111">Create an encryptor for the specified key</span></span>
            </summary>
        <returns><span data-ttu-id="8759a-112">データを暗号化するため、ICryptoTranform</span><span class="sxs-lookup"><span data-stu-id="8759a-112">An ICryptoTranform for encrypting data</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>