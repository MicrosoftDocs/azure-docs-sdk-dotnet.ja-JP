<Type Name="ICertificateOperations" FullName="Microsoft.Azure.Management.Batch.ICertificateOperations">
  <TypeSignature Language="C#" Value="public interface ICertificateOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICertificateOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.ICertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICertificateOperations" />
  <TypeSignature Language="F#" Value="type ICertificateOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d6ed2-101">CertificateOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-101">CertificateOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Certificate, class Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate, Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt;" Usage="iCertificateOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6ed2-102">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-102">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d6ed2-103">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-103">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="d6ed2-104">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-104">The identifier for the certificate.</span></span> <span data-ttu-id="d6ed2-105">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-105">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="d6ed2-106">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-106">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d6ed2-107">証明書の作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-107">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="d6ed2-108">更新する証明書のエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-108">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="d6ed2-109">値"\*"を証明書が既に存在する場合にのみ、操作を適用するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-109">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="d6ed2-110">省略した場合、この操作常に使用されます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-110">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="d6ed2-111">設定 ' \*'、新しい証明書を作成するが、既存の証明書の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-111">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="d6ed2-112">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-112">Other values will be ignored.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d6ed2-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6ed2-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6ed2-115">指定されたアカウント内の新しい証明書を作成します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-115">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d6ed2-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d6ed2-117">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-117">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d6ed2-118">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt;" Usage="iCertificateOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6ed2-119">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-119">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d6ed2-120">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-120">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="d6ed2-121">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-121">The identifier for the certificate.</span></span> <span data-ttu-id="d6ed2-122">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-122">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="d6ed2-123">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-123">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d6ed2-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6ed2-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6ed2-126">指定された証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-126">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d6ed2-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d6ed2-128">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-128">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCancelDeletionHeaders&gt;&gt; CancelDeletionWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Certificate, class Microsoft.Azure.Management.Batch.Models.CertificateCancelDeletionHeaders&gt;&gt; CancelDeletionWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.CancelDeletionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelDeletionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate, Microsoft.Azure.Management.Batch.Models.CertificateCancelDeletionHeaders&gt;&gt;" Usage="iCertificateOperations.CancelDeletionWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCancelDeletionHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6ed2-129">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-129">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d6ed2-130">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-130">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="d6ed2-131">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-131">The identifier for the certificate.</span></span> <span data-ttu-id="d6ed2-132">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-132">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="d6ed2-133">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-133">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d6ed2-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6ed2-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6ed2-136">指定されたアカウントからの証明書の削除に失敗をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-136">Cancels a failed deletion of a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="d6ed2-137">プールで使用されている証明書を削除またはコンピューティング ノードしようとすると、証明書の状態は deleteFailed に変更します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-137">If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed.</span></span> <span data-ttu-id="d6ed2-138">証明書の使用を続行することを決定する場合をアクティブに証明書の状態を設定します。 この操作を使用できます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-138">If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active.</span></span> <span data-ttu-id="d6ed2-139">証明書を削除する場合は、削除が失敗した後、この操作を実行する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-139">If you intend to delete the certificate, you do not need to run this operation after the deletion failed.</span></span> <span data-ttu-id="d6ed2-140">証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-140">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d6ed2-141">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d6ed2-142">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-142">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d6ed2-143">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Certificate, class Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate, Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt;" Usage="iCertificateOperations.CreateWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateCreateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6ed2-144">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-144">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d6ed2-145">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-145">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="d6ed2-146">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-146">The identifier for the certificate.</span></span> <span data-ttu-id="d6ed2-147">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-147">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="d6ed2-148">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-148">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d6ed2-149">証明書の作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-149">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="d6ed2-150">更新する証明書のエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-150">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="d6ed2-151">値"\*"を証明書が既に存在する場合にのみ、操作を適用するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-151">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="d6ed2-152">省略した場合、この操作常に使用されます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-152">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="d6ed2-153">設定 ' \*'、新しい証明書を作成するが、既存の証明書の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-153">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="d6ed2-154">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-154">Other values will be ignored.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d6ed2-155">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-155">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6ed2-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6ed2-157">指定されたアカウント内の新しい証明書を作成します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-157">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d6ed2-158">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-158">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d6ed2-159">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-159">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d6ed2-160">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-160">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt;" Usage="iCertificateOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6ed2-161">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-161">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d6ed2-162">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-162">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="d6ed2-163">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-163">The identifier for the certificate.</span></span> <span data-ttu-id="d6ed2-164">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-164">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="d6ed2-165">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-165">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d6ed2-166">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6ed2-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6ed2-168">指定された証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-168">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d6ed2-169">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d6ed2-170">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-170">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Certificate, class Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate, Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders&gt;&gt;" Usage="iCertificateOperations.GetWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6ed2-171">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-171">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d6ed2-172">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-172">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="d6ed2-173">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-173">The identifier for the certificate.</span></span> <span data-ttu-id="d6ed2-174">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-174">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="d6ed2-175">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-175">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d6ed2-176">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6ed2-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6ed2-178">指定された証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-178">Gets information about the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d6ed2-179">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-179">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d6ed2-180">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-180">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d6ed2-181">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt; ListByBatchAccountNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt; ListByBatchAccountNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.ListByBatchAccountNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByBatchAccountNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt;" Usage="iCertificateOperations.ListByBatchAccountNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="d6ed2-182">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-182">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d6ed2-183">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-183">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6ed2-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6ed2-185">すべての指定されたアカウントの証明書の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-185">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d6ed2-186">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-186">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d6ed2-187">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-187">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d6ed2-188">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-188">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt; ListByBatchAccountWithHttpMessagesAsync (string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt; ListByBatchAccountWithHttpMessagesAsync(string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.ListByBatchAccountWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByBatchAccountWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt;" Usage="iCertificateOperations.ListByBatchAccountWithHttpMessagesAsync (resourceGroupName, accountName, maxresults, select, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6ed2-189">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-189">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d6ed2-190">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-190">The name of the Batch account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="d6ed2-191">応答で返されるアイテムの最大数。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-191">The maximum number of items to return in the response.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="d6ed2-192">コンマ区切りのプロパティの一覧を返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-192">Comma separated list of properties that should be returned.</span></span> <span data-ttu-id="d6ed2-193">例:"のプロパティ/provisioningState"です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-193">e.g. "properties/provisioningState".</span></span> <span data-ttu-id="d6ed2-194">のみの上位レベル のプロパティのプロパティ/選択に対して有効です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-194">Only top level properties under properties/ are valid for selection.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="d6ed2-195">OData フィルター式です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-195">OData filter expression.</span></span> <span data-ttu-id="d6ed2-196">フィルター処理の有効なプロパティは"のプロパティ/provisioningState"、"のプロパティ/provisioningStateTransitionTime"、"name"です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-196">Valid properties for filtering are "properties/provisioningState", "properties/provisioningStateTransitionTime", "name".</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d6ed2-197">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-197">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6ed2-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6ed2-199">すべての指定されたアカウントの証明書の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-199">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d6ed2-200">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-200">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d6ed2-201">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-201">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d6ed2-202">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-202">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Certificate, class Microsoft.Azure.Management.Batch.Models.CertificateUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ICertificateOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate, Microsoft.Azure.Management.Batch.Models.CertificateUpdateHeaders&gt;&gt;" Usage="iCertificateOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, certificateName, parameters, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Certificate,Microsoft.Azure.Management.Batch.Models.CertificateUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d6ed2-203">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-203">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="d6ed2-204">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-204">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="d6ed2-205">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-205">The identifier for the certificate.</span></span> <span data-ttu-id="d6ed2-206">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-206">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="d6ed2-207">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-207">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d6ed2-208">証明書を更新するエンティティ。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-208">Certificate entity to update.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="d6ed2-209">更新する証明書のエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-209">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="d6ed2-210">この値を省略するかに設定することができます"\*"を無条件で操作を適用します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-210">This value can be omitted or set to "\*" to apply the operation unconditionally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d6ed2-211">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-211">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d6ed2-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d6ed2-213">既存の証明書のプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-213">Updates the properties of an existing certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="d6ed2-214">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-214">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d6ed2-215">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-215">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d6ed2-216">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d6ed2-216">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>