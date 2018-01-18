<Type Name="CertificateIssuerIdentifier" FullName="Microsoft.Azure.KeyVault.CertificateIssuerIdentifier">
  <TypeSignature Language="C#" Value="public sealed class CertificateIssuerIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CertificateIssuerIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.CertificateIssuerIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CertificateIssuerIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type CertificateIssuerIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            <span data-ttu-id="3fe03-101">Key Vault の発行者識別子です。</span><span class="sxs-lookup"><span data-stu-id="3fe03-101">The Key Vault issuer identifier.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateIssuerIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateIssuerIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.CertificateIssuerIdentifier : string -&gt; Microsoft.Azure.KeyVault.CertificateIssuerIdentifier" Usage="new Microsoft.Azure.KeyVault.CertificateIssuerIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier"><span data-ttu-id="3fe03-102">資格情報コンテナーの発行者識別子です。</span><span class="sxs-lookup"><span data-stu-id="3fe03-102">The key vault issuer identifier.</span></span></param>
        <summary>
            <span data-ttu-id="3fe03-103">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="3fe03-103">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateIssuerIdentifier (string vaultBaseUrl, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateIssuerIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.CertificateIssuerIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.CertificateIssuerIdentifier" Usage="new Microsoft.Azure.KeyVault.CertificateIssuerIdentifier (vaultBaseUrl, name)" />
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
        <param name="vaultBaseUrl"><span data-ttu-id="3fe03-104">資格情報コンテナーの基本 URL です。</span><span class="sxs-lookup"><span data-stu-id="3fe03-104">The vault base URL.</span></span></param>
        <param name="name"><span data-ttu-id="3fe03-105">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="3fe03-105">The name of the issuer.</span></span></param>
        <summary>
            <span data-ttu-id="3fe03-106">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="3fe03-106">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsIssuerIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsIssuerIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsIssuerIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateIssuerIdentifier.IsIssuerIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsIssuerIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsIssuerIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.CertificateIssuerIdentifier.IsIssuerIdentifier identifier" />
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
        <param name="identifier"><span data-ttu-id="3fe03-107">資格情報コンテナーの発行者識別子です。</span><span class="sxs-lookup"><span data-stu-id="3fe03-107">The key vault issuer identifier.</span></span></param>
        <summary>
            <span data-ttu-id="3fe03-108">資格情報コンテナーの発行者に識別子が属しているかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="3fe03-108">Verifies whether the identifier belongs to a key vault issuer.</span></span>
            </summary>
        <returns><span data-ttu-id="3fe03-109">資格情報コンテナーの発行者に識別子が属している場合は true。</span><span class="sxs-lookup"><span data-stu-id="3fe03-109">True if the identifier belongs to a key vault issuer.</span></span> <span data-ttu-id="3fe03-110">False それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="3fe03-110">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>