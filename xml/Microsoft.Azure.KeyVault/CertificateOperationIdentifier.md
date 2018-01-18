<Type Name="CertificateOperationIdentifier" FullName="Microsoft.Azure.KeyVault.CertificateOperationIdentifier">
  <TypeSignature Language="C#" Value="public sealed class CertificateOperationIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CertificateOperationIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.CertificateOperationIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CertificateOperationIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type CertificateOperationIdentifier = class&#xA;    inherit ObjectIdentifier" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.ObjectIdentifier</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7e69b-101">Key Vault の証明書操作の識別子。</span><span class="sxs-lookup"><span data-stu-id="7e69b-101">The Key Vault certificate operation identifier.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOperationIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateOperationIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.CertificateOperationIdentifier : string -&gt; Microsoft.Azure.KeyVault.CertificateOperationIdentifier" Usage="new Microsoft.Azure.KeyVault.CertificateOperationIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier"><span data-ttu-id="7e69b-102">証明書の操作の識別子の識別子。</span><span class="sxs-lookup"><span data-stu-id="7e69b-102">The identifier for certificate operation identifier.</span></span> </param>
        <summary>
            <span data-ttu-id="7e69b-103">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="7e69b-103">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOperationIdentifier (string vaultBaseUrl, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateOperationIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.CertificateOperationIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.CertificateOperationIdentifier" Usage="new Microsoft.Azure.KeyVault.CertificateOperationIdentifier (vaultBaseUrl, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl"> <span data-ttu-id="7e69b-104">資格情報コンテナーの基本 url です。</span><span class="sxs-lookup"><span data-stu-id="7e69b-104">the vault base url.</span></span> </param>
        <param name="name"><span data-ttu-id="7e69b-105">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="7e69b-105">the name of the certificate.</span></span></param>
        <summary>
            <span data-ttu-id="7e69b-106">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="7e69b-106">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCertificateOperationIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsCertificateOperationIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsCertificateOperationIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateOperationIdentifier.IsCertificateOperationIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsCertificateOperationIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsCertificateOperationIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.CertificateOperationIdentifier.IsCertificateOperationIdentifier identifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier"><span data-ttu-id="7e69b-107">資格情報コンテナー証明書の操作の識別子。</span><span class="sxs-lookup"><span data-stu-id="7e69b-107">The key vault certificate operation identifier.</span></span></param>
        <summary>
            <span data-ttu-id="7e69b-108">資格情報コンテナー証明書の操作に識別子が属しているかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="7e69b-108">Verifies whether the identifier belongs to a key vault certificate operation.</span></span>
            </summary>
        <returns><span data-ttu-id="7e69b-109">資格情報コンテナー証明書の操作に識別子が属している場合は true。</span><span class="sxs-lookup"><span data-stu-id="7e69b-109">True if the identifier belongs to a key vault certificate operation.</span></span> <span data-ttu-id="7e69b-110">False それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="7e69b-110">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>