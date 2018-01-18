<Type Name="DeletedCertificateIdentifier" FullName="Microsoft.Azure.KeyVault.DeletedCertificateIdentifier">
  <TypeSignature Language="C#" Value="public sealed class DeletedCertificateIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeletedCertificateIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.DeletedCertificateIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeletedCertificateIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type DeletedCertificateIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            <span data-ttu-id="970da-101">Key Vault では、証明書識別子を削除します。</span><span class="sxs-lookup"><span data-stu-id="970da-101">The Key Vault deleted certificate identifier.</span></span> <span data-ttu-id="970da-102">別名の recoveryId します。</span><span class="sxs-lookup"><span data-stu-id="970da-102">Aka the recoveryId.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedCertificateIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedCertificateIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.DeletedCertificateIdentifier : string -&gt; Microsoft.Azure.KeyVault.DeletedCertificateIdentifier" Usage="new Microsoft.Azure.KeyVault.DeletedCertificateIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier"><span data-ttu-id="970da-103">証明書が削除用の識別子。</span><span class="sxs-lookup"><span data-stu-id="970da-103">The identifier for the deleted certificate.</span></span> <span data-ttu-id="970da-104">別名が削除されないように、recoveryId を返します。</span><span class="sxs-lookup"><span data-stu-id="970da-104">Aka the recoveryId return from deletion.</span></span></param>
        <summary>
            <span data-ttu-id="970da-105">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="970da-105">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedCertificateIdentifier (string vaultBaseUrl, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedCertificateIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.DeletedCertificateIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.DeletedCertificateIdentifier" Usage="new Microsoft.Azure.KeyVault.DeletedCertificateIdentifier (vaultBaseUrl, name)" />
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
        <param name="vaultBaseUrl"> <span data-ttu-id="970da-106">資格情報コンテナーのベース URL</span><span class="sxs-lookup"><span data-stu-id="970da-106">the vault base URL</span></span></param>
        <param name="name"><span data-ttu-id="970da-107">削除済みの証明書の名前</span><span class="sxs-lookup"><span data-stu-id="970da-107">the name of the deleted certificate</span></span></param>
        <summary>
            <span data-ttu-id="970da-108">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="970da-108">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDeletedCertificateIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsDeletedCertificateIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsDeletedCertificateIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedCertificateIdentifier.IsDeletedCertificateIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsDeletedCertificateIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsDeletedCertificateIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.DeletedCertificateIdentifier.IsDeletedCertificateIdentifier identifier" />
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
        <param name="identifier"><span data-ttu-id="970da-109">資格情報コンテナーの証明書識別子です。</span><span class="sxs-lookup"><span data-stu-id="970da-109">The key vault certificate identifier.</span></span></param>
        <summary>
            <span data-ttu-id="970da-110">識別子が削除された KeyVault 証明書の有効な識別子であるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="970da-110">Verifies whether the identifier is a valid KeyVault deleted certificate identifier.</span></span>
            </summary>
        <returns><span data-ttu-id="970da-111">識別子は有効な場合は true。 KeyVault は、証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="970da-111">True if the identifier is a valid KeyVault deleted certificate.</span></span> <span data-ttu-id="970da-112">False それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="970da-112">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>