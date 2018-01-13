<Type Name="CryptoHelper" FullName="Microsoft.Azure.Management.StorSimple8000Series.CryptoHelper">
  <TypeSignature Language="C#" Value="public class CryptoHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CryptoHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.CryptoHelper" />
  <TypeSignature Language="VB.NET" Value="Public Class CryptoHelper" />
  <TypeSignature Language="F#" Value="type CryptoHelper = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c5427-101">暗号のヘルパー。</span><span class="sxs-lookup"><span data-stu-id="c5427-101">The crypto helper.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CryptoHelper ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.CryptoHelper.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptCipherAES">
      <MemberSignature Language="C#" Value="public static string DecryptCipherAES (string cipherText, string sharedSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string DecryptCipherAES(string cipherText, string sharedSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.CryptoHelper.DecryptCipherAES(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DecryptCipherAES (cipherText As String, sharedSecret As String) As String" />
      <MemberSignature Language="F#" Value="static member DecryptCipherAES : string * string -&gt; string" Usage="Microsoft.Azure.Management.StorSimple8000Series.CryptoHelper.DecryptCipherAES (cipherText, sharedSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cipherText" Type="System.String" />
        <Parameter Name="sharedSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cipherText"><span data-ttu-id="c5427-102">暗号テキスト。</span><span class="sxs-lookup"><span data-stu-id="c5427-102">The cipher text.</span></span></param>
        <param name="sharedSecret"><span data-ttu-id="c5427-103">共有シークレット。</span><span class="sxs-lookup"><span data-stu-id="c5427-103">The shared secret.</span></span></param>
        <summary>
            <span data-ttu-id="c5427-104">AES アルゴリズムを使用して、指定された暗号化テキストを復号化されます。</span><span class="sxs-lookup"><span data-stu-id="c5427-104">The AES algorithm is used to decrypt the given cipherText.</span></span>
            </summary>
        <returns><span data-ttu-id="c5427-105">ペインのテキストで暗号化が解除されたシークレット。</span><span class="sxs-lookup"><span data-stu-id="c5427-105">The decrypted secret in pain text.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptSecretRSAPKCS">
      <MemberSignature Language="C#" Value="public static string EncryptSecretRSAPKCS (string plainText, string publicCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string EncryptSecretRSAPKCS(string plainText, string publicCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.CryptoHelper.EncryptSecretRSAPKCS(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EncryptSecretRSAPKCS (plainText As String, publicCertificate As String) As String" />
      <MemberSignature Language="F#" Value="static member EncryptSecretRSAPKCS : string * string -&gt; string" Usage="Microsoft.Azure.Management.StorSimple8000Series.CryptoHelper.EncryptSecretRSAPKCS (plainText, publicCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="plainText" Type="System.String" />
        <Parameter Name="publicCertificate" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="plainText"><span data-ttu-id="c5427-106">プレーン テキストでシークレット。</span><span class="sxs-lookup"><span data-stu-id="c5427-106">The secret in plain text.</span></span></param>
        <param name="publicCertificate"><span data-ttu-id="c5427-107">暗号化に使用する公開証明書。</span><span class="sxs-lookup"><span data-stu-id="c5427-107">The public certificate to be used for encryption.</span></span></param>
        <summary>
            <span data-ttu-id="c5427-108">このメソッドは、パブリック証明書を使用して、指定されたシークレットを暗号化します。</span><span class="sxs-lookup"><span data-stu-id="c5427-108">This method encrypts a given secret using the public certificate.</span></span>
            </summary>
        <returns><span data-ttu-id="c5427-109">暗号化されたシークレット。</span><span class="sxs-lookup"><span data-stu-id="c5427-109">The encrypted secret.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>