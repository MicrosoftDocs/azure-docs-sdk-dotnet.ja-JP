<Type Name="IAppServiceCertificateOrdersOperations" FullName="Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations">
  <TypeSignature Language="C#" Value="public interface IAppServiceCertificateOrdersOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServiceCertificateOrdersOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServiceCertificateOrdersOperations" />
  <TypeSignature Language="F#" Value="type IAppServiceCertificateOrdersOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="42ba5-101">AppServiceCertificateOrdersOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-101">AppServiceCertificateOrdersOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; BeginCreateOrUpdateCertificateWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; BeginCreateOrUpdateCertificateWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.BeginCreateOrUpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.BeginCreateOrUpdateCertificateWithHttpMessagesAsync (resourceGroupName, certificateOrderName, name, keyVaultCertificate, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-102">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-102">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-103">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-103">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="42ba5-104">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-104">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="42ba5-105">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="42ba5-105">Key vault certificate resource Id.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-108">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-108">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-109">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-109">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, certificateOrderName, certificateDistinguishedName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-113">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-113">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-114">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-114">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="42ba5-115">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="42ba5-115">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-116">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-116">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-118">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-118">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-119">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-119">Create or update a certificate purchase order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; CreateOrUpdateCertificateWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; CreateOrUpdateCertificateWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource keyVaultCertificate, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.CreateOrUpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.CreateOrUpdateCertificateWithHttpMessagesAsync (resourceGroupName, certificateOrderName, name, keyVaultCertificate, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-123">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-123">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-124">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-124">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="42ba5-125">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-125">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="42ba5-126">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="42ba5-126">Key vault certificate resource Id.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-129">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-129">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-130">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-130">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-131">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-132">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-132">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder certificateDistinguishedName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, certificateOrderName, certificateDistinguishedName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-134">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-134">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-135">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-135">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="42ba5-136">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="42ba5-136">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-137">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-139">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-139">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-140">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-140">Create or update a certificate purchase order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-141">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-142">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-142">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-143">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteCertificateWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteCertificateWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.DeleteCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceCertificateOrdersOperations.DeleteCertificateWithHttpMessagesAsync (resourceGroupName, certificateOrderName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-144">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-145">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-145">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="42ba5-146">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-146">Name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-147">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-147">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-149">証明書の順序に関連付けられている証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-149">Delete the certificate associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-150">証明書の順序に関連付けられている証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-150">Delete the certificate associated with a certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-151">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-152">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-152">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceCertificateOrdersOperations.DeleteWithHttpMessagesAsync (resourceGroupName, certificateOrderName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-153">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-153">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-154">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-154">Name of the certificate order.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-155">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-155">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-157">既存の証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-157">Delete an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-158">既存の証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-158">Delete an existing certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-159">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-159">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-160">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-160">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; GetCertificateWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; GetCertificateWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.GetCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.GetCertificateWithHttpMessagesAsync (resourceGroupName, certificateOrderName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-161">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-161">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-162">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-162">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="42ba5-163">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-163">Name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-164">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-164">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-166">証明書の順序に関連付けられている証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-166">Get the certificate associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-167">証明書の順序に関連付けられている証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-167">Get the certificate associated with a certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-168">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-168">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-169">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-169">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-170">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-170">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.GetWithHttpMessagesAsync (resourceGroupName, certificateOrderName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-171">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-171">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-172">証明書の順序の名前。</span><span class="sxs-lookup"><span data-stu-id="42ba5-172">Name of the certificate order..</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-175">証明書の順序を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-175">Get a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-176">証明書の順序を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-176">Get a certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-177">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-177">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-178">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-178">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-179">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-179">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="42ba5-180">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-180">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-181">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-181">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-182">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-183">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-183">Get certificate orders in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-184">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-184">Get certificate orders in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-185">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-185">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-186">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-186">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-187">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-187">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-188">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-188">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-189">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-191">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-191">Get certificate orders in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-192">リソース グループ内の証明書の注文を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-192">Get certificate orders in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-193">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-193">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-194">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-194">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-195">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-195">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;&gt; ListCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;&gt; ListCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.ListCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.ListCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="42ba5-196">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-196">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-197">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-197">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-199">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-199">List all certificates associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-200">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-200">List all certificates associated with a certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-201">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-201">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-202">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-202">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-203">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-203">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;&gt; ListCertificatesWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;&gt; ListCertificatesWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.ListCertificatesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListCertificatesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.ListCertificatesWithHttpMessagesAsync (resourceGroupName, certificateOrderName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-204">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-204">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-205">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-205">Name of the certificate order.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-206">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-206">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-208">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-208">List all certificates associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-209">証明書の順序に関連付けられているすべての証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-209">List all certificates associated with a certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-210">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-210">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-211">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-211">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-212">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-212">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="42ba5-213">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-213">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-214">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-214">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-215">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-215">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-216">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-216">List all certificate orders in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-217">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-217">List all certificate orders in a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-218">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-218">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-219">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-219">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-220">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-220">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-221">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-221">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-222">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-223">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-223">List all certificate orders in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-224">サブスクリプションのすべての証明書の注文を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-224">List all certificate orders in a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-225">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-225">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-226">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-226">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-227">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-227">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReissueWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ReissueWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest reissueCertificateOrderRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ReissueWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest reissueCertificateOrderRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.ReissueWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReissueWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceCertificateOrdersOperations.ReissueWithHttpMessagesAsync (resourceGroupName, certificateOrderName, reissueCertificateOrderRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="reissueCertificateOrderRequest" Type="Microsoft.Azure.Management.WebSites.Models.ReissueCertificateOrderRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-228">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-228">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-229">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-229">Name of the certificate order.</span></span>
            </param>
        <param name="reissueCertificateOrderRequest">
            <span data-ttu-id="42ba5-230">パラメーター、再実行してください。</span><span class="sxs-lookup"><span data-stu-id="42ba5-230">Parameters for the reissue.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-231">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-231">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-232">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-232">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-233">既存の証明書の順序を再実行します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-233">Reissue an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-234">既存の証明書の順序を再実行します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-234">Reissue an existing certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-235">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-235">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-236">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-236">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RenewWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RenewWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest renewCertificateOrderRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RenewWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest renewCertificateOrderRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.RenewWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RenewWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceCertificateOrdersOperations.RenewWithHttpMessagesAsync (resourceGroupName, certificateOrderName, renewCertificateOrderRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="renewCertificateOrderRequest" Type="Microsoft.Azure.Management.WebSites.Models.RenewCertificateOrderRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-237">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-237">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-238">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-238">Name of the certificate order.</span></span>
            </param>
        <param name="renewCertificateOrderRequest">
            <span data-ttu-id="42ba5-239">パラメーターを更新します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-239">Renew parameters</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-240">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-240">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-241">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-241">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-242">既存の証明書の順序を更新します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-242">Renew an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-243">既存の証明書の順序を更新します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-243">Renew an existing certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-244">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-244">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-245">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-245">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResendEmailWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ResendEmailWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ResendEmailWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.ResendEmailWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResendEmailWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceCertificateOrdersOperations.ResendEmailWithHttpMessagesAsync (resourceGroupName, certificateOrderName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-246">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-246">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-247">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-247">Name of the certificate order.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-248">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-248">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-250">証明書の電子メールの再送信します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-250">Resend certificate email.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-251">証明書の電子メールの再送信します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-251">Resend certificate email.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-252">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-252">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-253">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-253">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResendRequestEmailsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ResendRequestEmailsWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.NameIdentifier nameIdentifier, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ResendRequestEmailsWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.NameIdentifier nameIdentifier, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.ResendRequestEmailsWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.NameIdentifier,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResendRequestEmailsWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.NameIdentifier * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceCertificateOrdersOperations.ResendRequestEmailsWithHttpMessagesAsync (resourceGroupName, certificateOrderName, nameIdentifier, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="nameIdentifier" Type="Microsoft.Azure.Management.WebSites.Models.NameIdentifier" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-254">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-254">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-255">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-255">Name of the certificate order.</span></span>
            </param>
        <param name="nameIdentifier">
            <span data-ttu-id="42ba5-256">電子メール アドレス</span><span class="sxs-lookup"><span data-stu-id="42ba5-256">Email address</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-257">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-257">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-258">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-259">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-259">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-260">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-260">Verify domain ownership for this certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-261">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-261">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-262">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-262">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateActionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt;&gt;&gt; RetrieveCertificateActionsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt;&gt;&gt; RetrieveCertificateActionsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.RetrieveCertificateActionsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RetrieveCertificateActionsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt;&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.RetrieveCertificateActionsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderAction&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-263">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-263">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="42ba5-264">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-264">Name of the certificate order.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-265">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-265">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-266">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-266">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-267">証明書の操作の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-267">Retrieve the list of certificate actions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-268">証明書の操作の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-268">Retrieve the list of certificate actions.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-269">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-269">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-270">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-270">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-271">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-271">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateEmailHistoryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt;&gt;&gt; RetrieveCertificateEmailHistoryWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt;&gt;&gt; RetrieveCertificateEmailHistoryWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.RetrieveCertificateEmailHistoryWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RetrieveCertificateEmailHistoryWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt;&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.RetrieveCertificateEmailHistoryWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.CertificateEmail&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-272">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-272">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="42ba5-273">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-273">Name of the certificate order.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-274">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-274">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-275">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-275">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-276">電子メールの履歴を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-276">Retrieve email history.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-277">電子メールの履歴を取得します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-277">Retrieve email history.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-278">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-278">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-279">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-279">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-280">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-280">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RetrieveSiteSealWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SiteSeal&gt;&gt; RetrieveSiteSealWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.SiteSealRequest siteSealRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.SiteSeal&gt;&gt; RetrieveSiteSealWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.SiteSealRequest siteSealRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.RetrieveSiteSealWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.SiteSealRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RetrieveSiteSealWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.SiteSealRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SiteSeal&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.RetrieveSiteSealWithHttpMessagesAsync (resourceGroupName, certificateOrderName, siteSealRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SiteSeal&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="siteSealRequest" Type="Microsoft.Azure.Management.WebSites.Models.SiteSealRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-281">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-281">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-282">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-282">Name of the certificate order.</span></span>
            </param>
        <param name="siteSealRequest">
            <span data-ttu-id="42ba5-283">サイトでは、要求を封印します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-283">Site seal request.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-284">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-284">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-285">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-285">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-286">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-286">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-287">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-287">Verify domain ownership for this certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-288">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-288">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-289">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-289">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-290">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-290">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; UpdateCertificateWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource keyVaultCertificate, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt; UpdateCertificateWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource keyVaultCertificate, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.UpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.UpdateCertificateWithHttpMessagesAsync (resourceGroupName, certificateOrderName, name, keyVaultCertificate, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificatePatchResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-291">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-291">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-292">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-292">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="42ba5-293">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-293">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="42ba5-294">資格情報コンテナー証明書リソース id。</span><span class="sxs-lookup"><span data-stu-id="42ba5-294">Key vault certificate resource Id.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-295">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-295">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-296">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-296">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-297">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-297">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-298">作成し、証明書を更新または key vault シークレットに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-298">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-299">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-299">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-300">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-300">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-301">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-301">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource certificateDistinguishedName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource certificateDistinguishedName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;" Usage="iAppServiceCertificateOrdersOperations.UpdateWithHttpMessagesAsync (resourceGroupName, certificateOrderName, certificateDistinguishedName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-302">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-302">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-303">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-303">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="42ba5-304">証明書の順序を使用するための識別名。</span><span class="sxs-lookup"><span data-stu-id="42ba5-304">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-305">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-305">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-306">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-306">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-307">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-307">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-308">作成または、購買発注の証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-308">Create or update a certificate purchase order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-309">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-309">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="42ba5-310">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-310">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-311">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-311">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ValidatePurchaseInformationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ValidatePurchaseInformationWithHttpMessagesAsync (Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder appServiceCertificateOrder, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ValidatePurchaseInformationWithHttpMessagesAsync(class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder appServiceCertificateOrder, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.ValidatePurchaseInformationWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidatePurchaseInformationWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceCertificateOrdersOperations.ValidatePurchaseInformationWithHttpMessagesAsync (appServiceCertificateOrder, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appServiceCertificateOrder" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrder" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="appServiceCertificateOrder">
            <span data-ttu-id="42ba5-312">証明書の順序の情報です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-312">Information for a certificate order.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-313">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-313">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-314">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-314">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-315">証明書の順序の情報を検証します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-315">Validate information for a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-316">証明書の順序の情報を検証します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-316">Validate information for a certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-317">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-317">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-318">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-318">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; VerifyDomainOwnershipWithHttpMessagesAsync (string resourceGroupName, string certificateOrderName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; VerifyDomainOwnershipWithHttpMessagesAsync(string resourceGroupName, string certificateOrderName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations.VerifyDomainOwnershipWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnershipWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceCertificateOrdersOperations.VerifyDomainOwnershipWithHttpMessagesAsync (resourceGroupName, certificateOrderName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ba5-319">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-319">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="42ba5-320">証明書の順序の名前です。</span><span class="sxs-lookup"><span data-stu-id="42ba5-320">Name of the certificate order.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="42ba5-321">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-321">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ba5-322">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="42ba5-322">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ba5-323">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-323">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="42ba5-324">この証明書の順序のドメインの所有権を確認します。</span><span class="sxs-lookup"><span data-stu-id="42ba5-324">Verify domain ownership for this certificate order.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="42ba5-325">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-325">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="42ba5-326">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="42ba5-326">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>