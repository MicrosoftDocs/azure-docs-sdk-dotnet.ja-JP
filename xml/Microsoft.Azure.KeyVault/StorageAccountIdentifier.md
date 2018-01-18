<Type Name="StorageAccountIdentifier" FullName="Microsoft.Azure.KeyVault.StorageAccountIdentifier">
  <TypeSignature Language="C#" Value="public sealed class StorageAccountIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StorageAccountIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.StorageAccountIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageAccountIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type StorageAccountIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            <span data-ttu-id="3d244-101">Key Vault のストレージ アカウントの識別子です。</span><span class="sxs-lookup"><span data-stu-id="3d244-101">The Key Vault storage account identifier.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.StorageAccountIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.StorageAccountIdentifier : string -&gt; Microsoft.Azure.KeyVault.StorageAccountIdentifier" Usage="new Microsoft.Azure.KeyVault.StorageAccountIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier"><span data-ttu-id="3d244-102">Key Vault のストレージ アカウントの識別子です。</span><span class="sxs-lookup"><span data-stu-id="3d244-102">The Key Vault storage account identifier.</span></span></param>
        <summary>
            <span data-ttu-id="3d244-103">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="3d244-103">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountIdentifier (string vaultBaseUrl, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.StorageAccountIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.StorageAccountIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.StorageAccountIdentifier" Usage="new Microsoft.Azure.KeyVault.StorageAccountIdentifier (vaultBaseUrl, name)" />
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
        <param name="vaultBaseUrl"><span data-ttu-id="3d244-104">資格情報コンテナーの基本 URL です。</span><span class="sxs-lookup"><span data-stu-id="3d244-104">The vault base URL.</span></span></param>
        <param name="name"><span data-ttu-id="3d244-105">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="3d244-105">The name of the storage account.</span></span></param>
        <summary>
            <span data-ttu-id="3d244-106">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="3d244-106">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsStorageAccountIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsStorageAccountIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsStorageAccountIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.StorageAccountIdentifier.IsStorageAccountIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsStorageAccountIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsStorageAccountIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.StorageAccountIdentifier.IsStorageAccountIdentifier identifier" />
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
        <param name="identifier"><span data-ttu-id="3d244-107">資格情報コンテナーのストレージ アカウントの識別子です。</span><span class="sxs-lookup"><span data-stu-id="3d244-107">The key vault storage account identifier.</span></span></param>
        <summary>
            <span data-ttu-id="3d244-108">識別子がキー資格情報コンテナーのストレージ アカウントに属しているかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="3d244-108">Verifies whether the identifier belongs to a key vault storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="3d244-109">識別子は、資格情報コンテナーのストレージ アカウントに属している場合は true。</span><span class="sxs-lookup"><span data-stu-id="3d244-109">True if the identifier belongs to a key vault storage account.</span></span> <span data-ttu-id="3d244-110">False それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="3d244-110">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>