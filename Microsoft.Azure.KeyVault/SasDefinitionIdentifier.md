<Type Name="SasDefinitionIdentifier" FullName="Microsoft.Azure.KeyVault.SasDefinitionIdentifier">
  <TypeSignature Language="C#" Value="public sealed class SasDefinitionIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SasDefinitionIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.SasDefinitionIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SasDefinitionIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type SasDefinitionIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            <span data-ttu-id="800bd-101">Key Vault ストレージの SAS 定義識別子です。</span><span class="sxs-lookup"><span data-stu-id="800bd-101">The Key Vault storage SAS definition identifier.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.SasDefinitionIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.SasDefinitionIdentifier : string -&gt; Microsoft.Azure.KeyVault.SasDefinitionIdentifier" Usage="new Microsoft.Azure.KeyVault.SasDefinitionIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier"><span data-ttu-id="800bd-102">記憶域 SAS の資格情報コンテナー定義識別子です。</span><span class="sxs-lookup"><span data-stu-id="800bd-102">The key vault storage SAS definition identifier.</span></span></param>
        <summary>
            <span data-ttu-id="800bd-103">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="800bd-103">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionIdentifier (string vaultBaseUrl, string storageAccountName, string sasDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string storageAccountName, string sasDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.SasDefinitionIdentifier.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, storageAccountName As String, sasDefinitionName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.SasDefinitionIdentifier : string * string * string -&gt; Microsoft.Azure.KeyVault.SasDefinitionIdentifier" Usage="new Microsoft.Azure.KeyVault.SasDefinitionIdentifier (vaultBaseUrl, storageAccountName, sasDefinitionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl"><span data-ttu-id="800bd-104">資格情報コンテナーの基本 URL です。</span><span class="sxs-lookup"><span data-stu-id="800bd-104">The vault base URL.</span></span></param>
        <param name="storageAccountName"><span data-ttu-id="800bd-105">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="800bd-105">The name of the storage account.</span></span></param>
        <param name="sasDefinitionName"><span data-ttu-id="800bd-106">記憶域の SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="800bd-106">The name of the storage SAS definition.</span></span></param>
        <summary>
            <span data-ttu-id="800bd-107">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="800bd-107">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSasDefinitionIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsSasDefinitionIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsSasDefinitionIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.SasDefinitionIdentifier.IsSasDefinitionIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsSasDefinitionIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsSasDefinitionIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.SasDefinitionIdentifier.IsSasDefinitionIdentifier identifier" />
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
        <param name="identifier"><span data-ttu-id="800bd-108">記憶域 SAS の資格情報コンテナー定義識別子です。</span><span class="sxs-lookup"><span data-stu-id="800bd-108">The key vault storage SAS definition identifier.</span></span></param>
        <summary>
            <span data-ttu-id="800bd-109">資格情報コンテナーのキー記憶域 SAS 定義に識別子が属しているかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="800bd-109">Verifies whether the identifier belongs to a key vault storage SAS definition.</span></span>
            </summary>
        <returns><span data-ttu-id="800bd-110">資格情報コンテナーのキー記憶域 SAS 定義に識別子が属している場合は true。</span><span class="sxs-lookup"><span data-stu-id="800bd-110">True if the identifier belongs to a key vault storage SAS definition.</span></span> <span data-ttu-id="800bd-111">False それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="800bd-111">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public string StorageAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.SasDefinitionIdentifier.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccount As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : string with get, set" Usage="Microsoft.Azure.KeyVault.SasDefinitionIdentifier.StorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>