<Type Name="IWithKeyVault" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault">
  <TypeSignature Language="C#" Value="public interface IWithKeyVault" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithKeyVault" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithKeyVault" />
  <TypeSignature Language="F#" Value="type IWithKeyVault = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="238be-101">アプリケーション サービス証明書の順序の定義以上のドメインを設定する検証メソッドを許可します。</span><span class="sxs-lookup"><span data-stu-id="238be-101">An app service certificate order definition allowing more domain verification methods to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingKeyVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate WithExistingKeyVault (Microsoft.Azure.Management.KeyVault.Fluent.IVault vault);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate WithExistingKeyVault(class Microsoft.Azure.Management.KeyVault.Fluent.IVault vault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault.WithExistingKeyVault(Microsoft.Azure.Management.KeyVault.Fluent.IVault)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingKeyVault (vault As IVault) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingKeyVault : Microsoft.Azure.Management.KeyVault.Fluent.IVault -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate" Usage="iWithKeyVault.WithExistingKeyVault vault" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vault" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVault" />
      </Parameters>
      <Docs>
        <param name="vault"><span data-ttu-id="238be-102">秘密キーを格納するコンテナーです。</span><span class="sxs-lookup"><span data-stu-id="238be-102">The vault to store the private key.</span></span></param>
        <summary>
            <span data-ttu-id="238be-103">証明書の秘密キーを格納する、既存のキー コンテナーを指定します。</span><span class="sxs-lookup"><span data-stu-id="238be-103">Specifies an existing key vault to store the certificate private key.</span></span>
            <span data-ttu-id="238be-104">資格情報コンテナーは、機密データの読み取り/書き込みに 2 つのサービス プリンシパルを許可する必要があります: f3c21649-0979-4721-ac85-b0216b2cf413 と abfa0a7c-a6b6-4736-8310-5855508787 cd。</span><span class="sxs-lookup"><span data-stu-id="238be-104">The vault MUST allow 2 service principals to read/write secrets: f3c21649-0979-4721-ac85-b0216b2cf413 and abfa0a7c-a6b6-4736-8310-5855508787cd.</span></span>
            <span data-ttu-id="238be-105">アクセスを持たない場合、試行されますアクセス権を付与します。</span><span class="sxs-lookup"><span data-stu-id="238be-105">If they don't have access, an attempt will be made to grant access.</span></span> <span data-ttu-id="238be-106">Active Directory Graph にアクセスすることがなく、id に記録は、この試行は失敗します。</span><span class="sxs-lookup"><span data-stu-id="238be-106">If you are logged in from an identity without access to the Active Directory Graph, this attempt will fail.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="238be-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="238be-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewKeyVault">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate WithNewKeyVault (string vaultName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate WithNewKeyVault(string vaultName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithKeyVault.WithNewKeyVault(System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member WithNewKeyVault : string * Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate" Usage="iWithKeyVault.WithNewKeyVault (vaultName, region)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="vaultName"><span data-ttu-id="238be-108">新しいキー資格情報コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="238be-108">The name of the new key vault.</span></span></param>
        <param name="region"><span data-ttu-id="238be-109">資格情報コンテナーを作成する領域。</span><span class="sxs-lookup"><span data-stu-id="238be-109">The region to create the vault.</span></span></param>
        <summary>
            <span data-ttu-id="238be-110">証明書の秘密キーを格納する新しい key vault を作成します。</span><span class="sxs-lookup"><span data-stu-id="238be-110">Creates a new key vault to store the certificate private key.</span></span>
            <span data-ttu-id="238be-111">Active Directory Graph にアクセスすることがなく、id ログインしている場合は、このメソッドを使用しないでください。</span><span class="sxs-lookup"><span data-stu-id="238be-111">DO NOT use this method if you are logged in from an identity without access to the Active Directory Graph.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="238be-112">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="238be-112">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>