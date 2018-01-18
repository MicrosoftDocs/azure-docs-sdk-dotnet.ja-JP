<Type Name="ICertificatesOperations" FullName="Microsoft.Azure.Management.IotHub.ICertificatesOperations">
  <TypeSignature Language="C#" Value="public interface ICertificatesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICertificatesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.ICertificatesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICertificatesOperations" />
  <TypeSignature Language="F#" Value="type ICertificatesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0b99-101">CertificatesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c0b99-101">CertificatesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;" Usage="iCertificatesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, certificateDescription, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateDescription" Type="Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0b99-102">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-102">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c0b99-103">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-103">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c0b99-104">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="c0b99-104">The name of the certificate</span></span>
            </param>
        <param name="certificateDescription">
            <span data-ttu-id="c0b99-105">証明書の本文。</span><span class="sxs-lookup"><span data-stu-id="c0b99-105">The certificate body.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c0b99-106">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="c0b99-106">ETag of the Certificate.</span></span> <span data-ttu-id="c0b99-107">新しい証明書を作成するのには指定しません。</span><span class="sxs-lookup"><span data-stu-id="c0b99-107">Do not specify for creating a brand new certificate.</span></span> <span data-ttu-id="c0b99-108">既存の証明書の更新に必要です。</span><span class="sxs-lookup"><span data-stu-id="c0b99-108">Required to update an existing certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0b99-109">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-109">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0b99-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0b99-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0b99-111">IoT hub を証明書をアップロードします。</span><span class="sxs-lookup"><span data-stu-id="c0b99-111">Upload the certificate to the IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c0b99-112">新規に追加するか、既存の証明書を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-112">Adds new or replaces existing certificate.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c0b99-113">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-113">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0b99-114">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-114">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0b99-115">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, string ifMatch, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCertificatesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0b99-116">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-116">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c0b99-117">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-117">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c0b99-118">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="c0b99-118">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c0b99-119">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="c0b99-119">ETag of the Certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0b99-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0b99-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0b99-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0b99-122">削除、X509 証明書。</span><span class="sxs-lookup"><span data-stu-id="c0b99-122">Delete an X509 certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c0b99-123">削除、既存 X509 証明書またはが存在しない場合、何も行われません。</span><span class="sxs-lookup"><span data-stu-id="c0b99-123">Deletes an existing X509 certificate or does nothing if it does not exist.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c0b99-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0b99-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GenerateVerificationCodeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt; GenerateVerificationCodeWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, string ifMatch, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt; GenerateVerificationCodeWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.GenerateVerificationCodeWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateVerificationCodeWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt;" Usage="iCertificatesOperations.GenerateVerificationCodeWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0b99-126">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-126">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c0b99-127">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-127">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c0b99-128">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="c0b99-128">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c0b99-129">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="c0b99-129">ETag of the Certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0b99-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0b99-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0b99-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0b99-132">所有しているフローの証拠の確認コードを生成します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-132">Generate verification code for proof of possession flow.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c0b99-133">所有しているフローの証拠の確認コードを生成します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-133">Generates verification code for proof of possession flow.</span></span> <span data-ttu-id="c0b99-134">検証コードを使用して、リーフ証明書を生成するされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-134">The verification code will be used to generate a leaf certificate.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c0b99-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0b99-136">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-136">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0b99-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;" Usage="iCertificatesOperations.GetWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0b99-138">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-138">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c0b99-139">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-139">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c0b99-140">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="c0b99-140">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0b99-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0b99-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0b99-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0b99-143">証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-143">Get the certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c0b99-144">証明書を返します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-144">Returns the certificate.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c0b99-145">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-145">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0b99-146">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-146">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0b99-147">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByIotHubWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt; ListByIotHubWithHttpMessagesAsync (string resourceGroupName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt; ListByIotHubWithHttpMessagesAsync(string resourceGroupName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.ListByIotHubWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByIotHubWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt;" Usage="iCertificatesOperations.ListByIotHubWithHttpMessagesAsync (resourceGroupName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0b99-148">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-148">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c0b99-149">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-149">The name of the IoT hub.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0b99-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0b99-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0b99-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0b99-152">証明書の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-152">Get the certificate list.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c0b99-153">証明書の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-153">Returns the list of certificates.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c0b99-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0b99-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0b99-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VerifyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; VerifyWithHttpMessagesAsync (string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt; VerifyWithHttpMessagesAsync(string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.ICertificatesOperations.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;" Usage="iCertificatesOperations.VerifyWithHttpMessagesAsync (resourceGroupName, resourceName, certificateName, certificateVerificationBody, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVerificationBody" Type="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0b99-157">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-157">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c0b99-158">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="c0b99-158">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c0b99-159">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="c0b99-159">The name of the certificate</span></span>
            </param>
        <param name="certificateVerificationBody">
            <span data-ttu-id="c0b99-160">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="c0b99-160">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c0b99-161">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="c0b99-161">ETag of the Certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0b99-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0b99-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0b99-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0b99-164">証明書の秘密キーを所有していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-164">Verify certificate's private key possession.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c0b99-165">確認のアップロード前証明書によって発行されたリーフ証明書を提供することによって、証明書の秘密キーを所有しているを確認します。</span><span class="sxs-lookup"><span data-stu-id="c0b99-165">Verifies the certificate's private key possession by providing the leaf cert issued by the verifying pre uploaded certificate.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Management.IotHub.Models.ErrorDetailsException">
            <span data-ttu-id="c0b99-166">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-166">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0b99-167">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-167">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0b99-168">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0b99-168">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>