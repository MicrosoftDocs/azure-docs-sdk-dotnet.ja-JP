<Type Name="IVaultCertificatesOperations" FullName="Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations">
  <TypeSignature Language="C#" Value="public interface IVaultCertificatesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVaultCertificatesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVaultCertificatesOperations" />
  <TypeSignature Language="F#" Value="type IVaultCertificatesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c44fb-101">VaultCertificatesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c44fb-101">VaultCertificatesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string vaultName, string certificateName, Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest certificateRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string vaultName, string certificateName, class Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest certificateRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.IVaultCertificatesOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt;&gt;" Usage="iVaultCertificatesOperations.CreateWithHttpMessagesAsync (resourceGroupName, vaultName, certificateName, certificateRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultCertificateResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateRequest" Type="Microsoft.Azure.Management.RecoveryServices.Models.CertificateRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c44fb-102">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="c44fb-102">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="c44fb-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="c44fb-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c44fb-104">証明書のフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="c44fb-104">Certificate friendly name.</span></span>
            </param>
        <param name="certificateRequest">
            <span data-ttu-id="c44fb-105">コンテナーの証明書をアップロードするための入力パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c44fb-105">Input parameters for uploading the vault certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c44fb-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c44fb-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c44fb-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c44fb-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c44fb-108">リソースの証明書をアップロードします。</span><span class="sxs-lookup"><span data-stu-id="c44fb-108">Upload a certificate for a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c44fb-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c44fb-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c44fb-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c44fb-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c44fb-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c44fb-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>