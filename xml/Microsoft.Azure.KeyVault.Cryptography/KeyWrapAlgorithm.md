<Type Name="KeyWrapAlgorithm" FullName="Microsoft.Azure.KeyVault.Cryptography.KeyWrapAlgorithm">
  <TypeSignature Language="C#" Value="public abstract class KeyWrapAlgorithm : Microsoft.Azure.KeyVault.Cryptography.Algorithm" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit KeyWrapAlgorithm extends Microsoft.Azure.KeyVault.Cryptography.Algorithm" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Cryptography.KeyWrapAlgorithm" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class KeyWrapAlgorithm&#xA;Inherits Algorithm" />
  <TypeSignature Language="F#" Value="type KeyWrapAlgorithm = class&#xA;    inherit Algorithm" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Cryptography.Algorithm</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1a73d-101">抽象キー ラップ アルゴリズム</span><span class="sxs-lookup"><span data-stu-id="1a73d-101">An abstract Key Wrap Algorithm</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyWrapAlgorithm (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.KeyWrapAlgorithm.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Cryptography.KeyWrapAlgorithm : string -&gt; Microsoft.Azure.KeyVault.Cryptography.KeyWrapAlgorithm" Usage="new Microsoft.Azure.KeyVault.Cryptography.KeyWrapAlgorithm name" />
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
      <MemberSignature Language="C#" Value="public abstract System.Security.Cryptography.ICryptoTransform CreateDecryptor (byte[] key, byte[] iv);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Security.Cryptography.ICryptoTransform CreateDecryptor(unsigned int8[] key, unsigned int8[] iv) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.KeyWrapAlgorithm.CreateDecryptor(System.Byte[],System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateDecryptor (key As Byte(), iv As Byte()) As ICryptoTransform" />
      <MemberSignature Language="F#" Value="abstract member CreateDecryptor : byte[] * byte[] -&gt; System.Security.Cryptography.ICryptoTransform" Usage="keyWrapAlgorithm.CreateDecryptor (key, iv)" />
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
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="1a73d-102">キー</span><span class="sxs-lookup"><span data-stu-id="1a73d-102">The key</span></span></param>
        <param name="iv"><span data-ttu-id="1a73d-103">初期化ベクター</span><span class="sxs-lookup"><span data-stu-id="1a73d-103">The initialization vector</span></span></param>
        <summary>
            <span data-ttu-id="1a73d-104">指定されたキーの復号化の作成</span><span class="sxs-lookup"><span data-stu-id="1a73d-104">Crea a decryptor for the specified key</span></span>
            </summary>
        <returns><span data-ttu-id="1a73d-105">データを復号化、ICryptoTransform</span><span class="sxs-lookup"><span data-stu-id="1a73d-105">An ICryptoTransform for decrypting data</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEncryptor">
      <MemberSignature Language="C#" Value="public abstract System.Security.Cryptography.ICryptoTransform CreateEncryptor (byte[] key, byte[] iv);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Security.Cryptography.ICryptoTransform CreateEncryptor(unsigned int8[] key, unsigned int8[] iv) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.KeyWrapAlgorithm.CreateEncryptor(System.Byte[],System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateEncryptor (key As Byte(), iv As Byte()) As ICryptoTransform" />
      <MemberSignature Language="F#" Value="abstract member CreateEncryptor : byte[] * byte[] -&gt; System.Security.Cryptography.ICryptoTransform" Usage="keyWrapAlgorithm.CreateEncryptor (key, iv)" />
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
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="1a73d-106">キー</span><span class="sxs-lookup"><span data-stu-id="1a73d-106">The key</span></span></param>
        <param name="iv"><span data-ttu-id="1a73d-107">初期化ベクター</span><span class="sxs-lookup"><span data-stu-id="1a73d-107">The initialization vector</span></span></param>
        <summary>
            <span data-ttu-id="1a73d-108">指定されたキーの暗号化機能を作成します。</span><span class="sxs-lookup"><span data-stu-id="1a73d-108">Create an encryptor for the specified key</span></span>
            </summary>
        <returns><span data-ttu-id="1a73d-109">データを暗号化するため、ICryptoTranform</span><span class="sxs-lookup"><span data-stu-id="1a73d-109">An ICryptoTranform for encrypting data</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>